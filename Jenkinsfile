pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                // Pulls the code from the GitHub repository
                git 'https://github.com/YourGitHubUsername/website-project.git'
            }
        }                                    
        stage('Build') {
            steps {
                // Static websites typically don’t require building, so you can skip this
                echo 'No build step necessary for a static website.'
            }
        }
        stage('Test') {
            steps {
                // You can add any testing scripts here, or skip it for a static website
                echo 'No tests defined.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying website...'
                // You can add deployment steps like SCP to an EC2 instance or AWS S3 here
            }
        }
    }
}
