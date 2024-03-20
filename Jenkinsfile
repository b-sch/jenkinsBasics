pipeline {
    agent {
        docker { image 'node:20.11.1-alpine3.19' }
        args '-v /var/run/docker.sock:/var/run/docker.sock'
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}