pipeline {
    agent any
    stages {
        stage('verify version') {
            steps {
                echo "hello"
                echo "hey"
                sh 'touch test.txt'
            }
        }
        stage('build') {
        steps{

        sh 'NodeJS app.js'
        }
       }
    }
}
