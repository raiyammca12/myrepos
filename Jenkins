pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/your-username/your-repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // e.g., sh 'make build' or 'npm install'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // e.g., sh 'npm test'
            }
        }
    }
}
