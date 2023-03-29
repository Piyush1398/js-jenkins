pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                echo "hello"
                sh 'ls -l'
            }
        }
        stage('build') {
        steps{

        sh 'NodeJS app.js'
        }
       }
    }
}
