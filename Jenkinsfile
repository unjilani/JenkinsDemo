pipeline {
    agent any

    stages {
        stage('Execute shell scripting') {
            steps {
               script{
                sh 'chmod +x ./script2.sh'
                sh './script2.sh'
               }
            }
        }
    }
}