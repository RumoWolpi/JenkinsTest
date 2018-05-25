pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'echo $PATH'
                sh 'export PATH=/sbin:/usr/sbin:/usr/bin:/usr/local/bin'
                sh 'echo $PATH'
                sh 'npm install'
                sh 'node console-test.js'
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
