pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from GitHub
                git url: 'https://github.com/yourusername/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                // Build step (if applicable)
                echo 'Building the application...'
            }
        }

        stage('Test') {
            steps {
                // Testing step (if applicable)
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                // Deployment step (if applicable)
                echo 'Deploying application...'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed. Please check the logs.'
        }
    }
}
