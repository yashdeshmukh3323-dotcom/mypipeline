pipeline {
    agent any

    stages {
        stage('Dev') {
            steps {
                echo 'I am in Dev'
                sh 'git --version'
            }
        }
 stage('Testing') {
            steps {
                echo 'I am in Testing'
                sh 'python3 --version'
            }
        }
 stage('Production') {
            steps {
                echo 'I am in Production'
                sh 'docker --version'
            }
        }
    }
}
