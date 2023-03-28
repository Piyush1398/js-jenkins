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
        sh 'NodeJS app.js'
        }
       }
    }
}
