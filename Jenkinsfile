pipeline {
    agent any

    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
                // Add your dependency installation commands here
            }
        }
        stage('Test') {
            steps {
                bat 'npm test'
                // Add your test commands here
            }
        }
    }
}