pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout from Git successful'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage running'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage running'
            }
        }
    }

    post {
        success {
            echo 'Build SUCCESS!'
        }
        failure {
            echo 'Build FAILED!'
        }
    }
}

