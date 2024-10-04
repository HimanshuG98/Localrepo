pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Pull code from the GitHub repository
                git url: 'https://github.com/your-username/your-repo.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the application..."'
            }
        }
    }
}
