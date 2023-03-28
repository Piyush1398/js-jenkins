pipeline {
    agent node
    stages {
        stage('verify version') {
            steps {
                sh 'node --version'
            }
        }
        stage('build') {
        steps{
        sh 'php index.php'
        }
       }
    }
}
