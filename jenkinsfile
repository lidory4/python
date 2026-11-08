pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('runPython'){
            steps{
                sh 'python3 main.py'
            }
        }
    }
}