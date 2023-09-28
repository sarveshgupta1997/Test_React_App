pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'yarn install'
      }
    }
    stage('Build') {
      steps {
        sh 'yarn run build'
      }
    }
    stage('Start') {
      steps {
        sh 'yarn run start'
      }
    }
  }
}