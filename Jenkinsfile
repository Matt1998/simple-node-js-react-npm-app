pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-u root' 
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
