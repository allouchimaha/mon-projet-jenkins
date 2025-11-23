pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'mvn --version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'java -version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
