pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "building step"'
            }
        }
        stage('Test') {
            steps {
               sh 'echo "testing step"'
            }
        }
        stage('Deliver') {
            steps {
                sh 'echo "delivering step"'
            }
        }
    }
}