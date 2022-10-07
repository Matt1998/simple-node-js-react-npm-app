pipeline {
    agent {
        docker {
            image 'node:lts-bullseye-slim'
            alwaysPull true
            args '-u 1000:1000 -u root -p 3000:3000' 
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
