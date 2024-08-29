pipeline {
    agent any
    options {
        disableConcurrentBuilds()
        timeout(time: 20, unit: 'MINUTES')
    }
    stages {
        stage('Building') {
            steps {
                sh "echo 'Building...'"
            }
        }
        stage('Test') {
            steps {
                sh "echo 'Testing...'"
            }
        }
        stage('Releasing') {
            steps {
                sh "echo 'Releasing...'"
            }
        }
    }
}