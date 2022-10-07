pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim' 
            args '-u 1000:1000 -p 3000:3000' 
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
