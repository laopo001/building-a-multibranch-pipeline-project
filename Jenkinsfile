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
                sh 'echo master "Build"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo master "hello"'
            }
        }
    }
}
