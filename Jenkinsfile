pipeline {
    agent any

    tools {
        nodejs "node20"
    }

    stages {


        stage('Install') {
            steps {
                sh 'npm install'
            }
        }

        stage('lint') {
            steps {
                sh 'npm run lint'
            }
        }

    }
}