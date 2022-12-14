pipeline {
    agent any

    tool {
        npm
    }
    environment {
        CI = 'true'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo "Running test..."
            }
        }
    }
    
}