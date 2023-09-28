pipeline {
    agent any
    tools {
        nodejs "NodeJS 20.7.0"
    }
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('Start') {
            steps {
                sh 'npm run start'
            }
        }
    }
}
