pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                sh 'cat app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}