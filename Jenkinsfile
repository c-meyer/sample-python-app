pipeline {
    agent {
        docker {
            image "python:3.9-slim"
        }
    }
    stages {
        stage('Hello World') {
            steps {
                sh 'echo "Hello World"'
            }

        }
        stage('I am') {
            steps {
                sh 'which python'
            }
        }
        stage('Bye World') {
            steps {
                sh 'python --version'
            }
        }
    }
}
