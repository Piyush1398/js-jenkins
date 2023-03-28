pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                echo "hello"
            }
        }
        stage('build') {
        steps{
        sh 'node app.js'
        }
       }
    }
}
