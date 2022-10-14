pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                docker { image 'node:latest' }
            }
            steps {
                sh 'node --version'
            }
        }
        stage('Front-end') {
            agent {
                docker { image 'node:16.13.1' }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}
