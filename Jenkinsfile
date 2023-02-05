pipeline {
    agent {
        docker { 
            image 'python:3.10.7-alpine' 
            args '-u root:root'
        } 
    }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
