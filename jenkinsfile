pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                set node console-test.js
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}