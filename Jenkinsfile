pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'docker-compose down',
                sh 'docker-compose up -d'
            }
        }
    }
}