pipeline {
    agent any
    stages {
        stage("NPM Install"){
            steps {
                bat 'cd Student-Registry-App && npm install'
            }
        }
        stage("NPM Audit") {
            steps {
                bat 'cd Student-Registry-App && npm audit'
            }
        }
    }
}