pipeline {
    agent { label 'linux_node'}
     tools {
        maven 'maven3.8.3'
        }
    stages {
        stage ('Clean') {
           steps {
            sh 'mvn clean'
            }
        }
        stage ('Build') {
           steps {
            sh 'mvn compile'
            }
        }
        stage ('test') {
           steps {
            sh 'mvn test'
            }
        }
        stage ('Install') {
           steps {
            sh 'mvn install'
            }
        }
    }
}
