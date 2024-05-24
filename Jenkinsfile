pipeline {
    agent {
        label 'Dev'
    }
    stages {
        stage('hostname') {
            steps {
                sh 'hostname'
            }
        }
        stage('server details') {
            steps {
                sh 'uname -a'
            }
        }
        stage('memory details') {
            steps {
                sh 'free -h'
            }
        }
        stage('Disk details') {
            steps {
                sh 'df -kh'
            }
        }
    }
}

        }
    }
    }
}

