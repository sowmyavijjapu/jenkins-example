pipeline {
    agent { label 'linux_node'}
   
    stages {
        stage ('Hello') {
             tools {
        maven 'maven3.8.3'
        }
            steps {
            sh 'mvn --version'
            }
        }
    }
}
