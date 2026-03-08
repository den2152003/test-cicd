pipeline {
    agent any
    stages {
        // Bỏ stage Clone vì Jenkins tự làm rồi
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Lint') {
            steps {
                sh 'npm run lint'
            }
        }
    }
}