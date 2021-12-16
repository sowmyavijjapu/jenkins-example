pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            tools {
			maven ‘maven_3.8.3’
		}

            steps {
  
                    sh 'mvn clean compile'
                
            }
        }

        stage ('Testing Stage') {

            steps {
     
                    sh 'mvn test'
                
            }
        }


        stage ('Deployment Stage') {
            steps {
               
                    sh 'mvn deploy'
                
            }
        }
    }
}
