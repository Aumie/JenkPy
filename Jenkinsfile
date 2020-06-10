pipeline {
  agent { docker { image 'python:3.8.3' } }
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
