pipeline {
    agent { docker { image 'python:3.8.3' } }
    stages {
        stage('try') {
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('build') {
            steps {
                    sh 'python --version'
                }
            }
        stage('Test') {
            agent any
            steps {
                sh 'echo "Fail!";'//exit 1
            }
        }
    }
}