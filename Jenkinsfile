pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh "echo 'Hello World'"
                sh 'node console-test.js'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
