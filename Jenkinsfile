pipeline {
    agent {
        label 'docker' 
    }

    stages {
        stage('build') {
            agent {
                label 'docker' 
                docker { image 'node:16.13.1-alpine' } 
        }
            steps {
                sh 'node --version'
            }
        }
    }
}