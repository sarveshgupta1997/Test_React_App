pipeline {
  agent any
  triggers {
    scm '*'
  }
  stages {
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