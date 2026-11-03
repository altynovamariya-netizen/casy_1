pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'docker build -t myapp:latest .'
            }
        }
        stage('Push') {
            steps {
                sh 'docker push myapp:latest'
            }
        }
    }
}