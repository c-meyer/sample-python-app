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
        stage('Bye World') {
            steps {
                sh 'echo "Goodbye!"'
            }
        }
    }
}
