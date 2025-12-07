pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Tarunkumar-2005/jenkins-docker-demo.git'
            }
        }
        stage('Test') {
            steps {
                sh 'npm install'
            }
        }
        stage('test') {
            steps {
                echo 'running tests...'
            }
        }
    }
}