pipeline {
    agent { label 'linux_node'}
   
    stages {
        stage ('Hello') {
             tools {
        maven 'maven3.8.2'
        }
            steps {
            sh 'mvn --version'
            }
        }
    }
}
