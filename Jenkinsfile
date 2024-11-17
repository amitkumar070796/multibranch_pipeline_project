pipeline {
    agent any

    stages {
        stage('first stage - Code Build') {
            steps {
                sh 'echo "Code is build"'
            }
        }
       stage('second stage - Code Test') {
            steps {
                sh 'echo "Code has been tested successfully"'
            }
        }
        stage('Third stage - Deploy the code on  production01 server') {
            steps {
                sh 'echo "Code has been deployed successfully on the server"'
            }
        }
        stage('Fourth stage - Deploy the code on  production02 server') {
            steps {
                sh 'echo "Code has been deployed successfully on the server"'
            }
        }
    }
}
