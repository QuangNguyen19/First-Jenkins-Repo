pipeline {
	agent none
  stages {
  	stage('Maven Install') {
    	agent {
      	docker {
        	image 'maven:3.8.4-openjdk-11-slim'
        }
      }
      steps {
      	sh 'mvn --version'
      }
    }
  }
}