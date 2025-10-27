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
                echo "Building..."
            }
        }
    }
}
