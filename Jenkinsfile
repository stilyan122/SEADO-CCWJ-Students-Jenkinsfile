pipeline {
    agent any
    stages {
        stage ("Go to correct folder"){
            steps{
                bat 'cd Student-Registry-App' 
                bat 'dir' 
            }
        }
        stage("NPM Install"){
            steps {
                bat 'npm install'
            }
        }
        stage("NPM Audit"){
            steps {
                bat 'npm audit'
            }
        }
    }
}