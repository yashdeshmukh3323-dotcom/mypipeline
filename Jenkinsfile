pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev and Testing'
                sh 'git --version'        
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing and Testing'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production and Testing'
                sh 'docker --version'
            }
        }
    }
}
