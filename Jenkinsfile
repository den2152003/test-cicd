pipeline {
    agent any

    tools {
        nodejs "node20"
    }

    stages {

        stage('Install') {
            steps {
                // sh 'npm install'
                echo 'Skipping npm install for faster builds'
            }
        }

        stage('lint') {
            steps {
                // sh 'npm run lint'
                echo 'Skipping lint for faster builds'
            }
        }

    }
}