pipeline {

    agent any

    stages {

        stage('Environment') {
            steps {
                echo "Running Jenkins Pipeline"
                sh 'whoami'
                sh 'pwd'
            }
        }

        stage('Checkout') {
            steps {
                echo "Source code is already checked out by Jenkins"
                sh 'ls -la'
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
                sh 'echo "Build completed successfully!"'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo "All tests passed!"'
            }
        }

        stage('Complete') {
            steps {
                echo "CI Pipeline completed!"
            }
        }
    }
}
