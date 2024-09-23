pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/HimanshuG98/Localrepo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Add build commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add deployment commands here
            }
        }
    }
}
