pipeline {
    agent {
        docker {
            image 'node:11-alpine'
            args '-p 3000:3000'
        }
    }
    environment {
        CI = 'true' 
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Build deve"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Test deve"'
            }
        }
    }
}
