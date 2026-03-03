pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building project...'
                bat 'type app.txt'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}