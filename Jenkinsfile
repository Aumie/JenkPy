pipeline {
  agent { docker { image 'python:3.8.2' } }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
    stage('test') {
      steps {
        sh 'python test.py'
      }   
    }
  }
}
