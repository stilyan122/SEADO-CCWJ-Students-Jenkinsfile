pipeline {
    agent any
    stages {
        stage("NPM Install"){
            steps {
                bat 'cd Student-Registry-App' 
                bat 'npm install'
            }
        }
        stage("NPM Audit"){
            steps {
                bat 'cd Student-Registry-App' 
                bat 'npm audit'
            }
        }
    }
}