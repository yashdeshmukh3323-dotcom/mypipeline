pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev and devlopment'
                sh 'git --version'        
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing and devlopment'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production and devlopment'
                sh 'docker --version'
            }
        }
    }
}
