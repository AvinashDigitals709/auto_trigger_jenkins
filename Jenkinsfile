pipeline {
    agent any
    

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/AvinashDigitals709/auto_trigger_jenkins', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                sh 'echo Hello, Jenkins!'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Example: sh 'python -m unittest discover tests'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
                // Example: sh './deploy.sh'
            }
        }
    }
}
