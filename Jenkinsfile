pipeline {
  agent any
  stages {
    stage('Build Image') {
      steps {
        sh 'make test TARGET=centos7'
      }
    }
  }
}