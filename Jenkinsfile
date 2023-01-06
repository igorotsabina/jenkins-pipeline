pipeline {
    agent any

    stages {
        stage('Web sever Apache') {
            steps {
            sh 'apache2 -v'
            }
        }
        stage('Status') {
            steps {
                sh 'systemctl status apache2'
            }
        } 
    }
}
