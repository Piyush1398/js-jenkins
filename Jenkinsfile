pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                sh 'node --version'
            }
        }
        stage('build') {
        steps{
        sh 'node app.js'
        }
       }
    }
}
