pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
               script{
                sh 'chmod 666 ./script2.sh'
                sh './script2.sh'
               }
            }
        }
    }
}