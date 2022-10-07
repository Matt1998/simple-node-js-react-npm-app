pipeline {
    agent {
        docker {
            //image 'node:lts-bullseye-slim'
            image 'app:latest'
            alwaysPull false
            args '-u 1000:1000 -u root -p 3000:3000' 
            reuseNode true
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
