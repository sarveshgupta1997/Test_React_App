pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        yarn install
      }
    }
    stage('Build') {
      steps {
        yarn run build
      }
    }
    stage('Start') {
      steps {
        yarn run start
      }
    }
  }
}