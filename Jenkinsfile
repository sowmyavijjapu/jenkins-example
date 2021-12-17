pipeline {
    agent { label 'linux_node'}
    tools {
        maven 'maven3.8.3'
        }
    stages {
        stage ('Hello') {
            steps {
            sh 'mvn --version'
            }
        }
    }
}
