pipeline {
    agent {
        docker { image 'node:18' }
    }
    stages {
        stage('Install & Test') {
            steps {
                sh 'npm install'
                sh 'npm test'
            }
        }
    }
}