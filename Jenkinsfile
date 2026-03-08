pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/den2152003/test-cicd'
            }
        }

        stage('Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run') {
            steps {
                sh 'npm run lint'
            }
        }

    }
}