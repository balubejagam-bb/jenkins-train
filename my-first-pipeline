pipeline {
    agent any
    stages {
        stage('Build inside Docker') {
            steps {
                script {
                    sh 'docker run --rm node:16-alpine node -v'
                }
            }
        }
    }
}
