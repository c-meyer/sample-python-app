pipeline {
    agent any
    triggers {
        pollSCM 'H/5 * * * *'
    }
    stages {
        stage('Hello World') {
            steps {
                sh 'echo "Hello World"'
            }

        }
        stage('I am') {
            steps {
                sh 'echo "I am Jenkins."'
            }
        }
        stage('Bye World') {
            steps {
                sh 'echo "Goodbye!"'
            }
        }
    }
}
