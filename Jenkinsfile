pipeline {
    agent any

    stages {
        stage('Execute shell script') {
            steps {
               script{
                sh 'sudo chmod 777 ./script2.sh'
                sh 'sudo ./script2.sh'
               }
            }
        }
    }
}