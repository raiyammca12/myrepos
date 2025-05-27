pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout([$class: 'GitSCM',
                    branches: [[name: '*/main']],
                    userRemoteConfigs: [[
                        url: 'https://github.com/raiyammca12/myrepos.git',
                        credentialsId: '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'
                    ]]
                ])
            }
        }
        stage('Build') {
            steps {
                echo "Building...new"
            }
        }
    }
}
