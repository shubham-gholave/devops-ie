pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ code.cpp -o myprogram'
            }
        }
        stage('Test') {
            steps {
                sh './myprogram'
            }
        }
    }
}
