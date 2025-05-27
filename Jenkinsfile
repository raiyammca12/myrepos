pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM',
                    branches: [[name: '*/main']],
                    userRemoteConfigs: [[
                        url: 'https://github.com/raiyammca12/myrepos.git',
                        credentialsId: 'github-credentials'
                    ]]
                ])
            }
        }
        stage('Build') {
            steps {
                echo "Building..."
            }
        }
    }
}
