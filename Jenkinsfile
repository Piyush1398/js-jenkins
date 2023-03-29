pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                echo "hello"
                echo "hey"
                sh 'mkdir sample'
            }
        }
        stage('build') {
        steps{

        sh 'NodeJS app.js'
        }
       }
    }
}
