pipeline {
    agent any
    stages {
        stage('hostname') {
            steps {
                sh 'hostname'
            }
        }
        stage('server details'){
            steps {
                sh 'uname -a'
            }
        }
        stage('memory detais'){
            step{
                sh 'free -h'
            }
        }
        stage('Disk details'){
            steps{
                step
                sh 'df -kh'
            }
        }
    }


}
