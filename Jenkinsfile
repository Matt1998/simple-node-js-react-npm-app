pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-u Team-07' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
