pipeline {
    agent any

    stages {
        
        stage('Checkout GIT') {
            steps {
                echo 'Pulling...';
            }
        }
        
        stage('Testing MAVEN') {
            steps {
                sh """mvn -version"""
            }
        }
        
        
    }
}
