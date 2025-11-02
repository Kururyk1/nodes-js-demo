pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/kururyk1/nodejs-demo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'node index.js'
            }
        }
    }
}
