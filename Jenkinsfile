pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code loaded from GitHub'
            }
        }

        stage('Test') {
            steps {
                echo 'Python tests will run in the configured build environment'
            }
        }

        stage('Docker Build') {
            steps {
                echo 'Docker build stage'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed. Check the console output.'
        }
    }
}
