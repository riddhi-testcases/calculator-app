pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 -m pytest'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo Deploying calculator app....'
            }
        }
    }
}