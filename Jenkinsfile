pipeline {
	agent none
  stages {
  	stage('Test') {
    	agent {
      	docker {
        	image 'node:16.13.1-alpine'
        }
      }
      steps {
      	sh 'node --version'
      }
    }
  }
}
