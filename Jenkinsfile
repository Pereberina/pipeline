#!/usr/bin/env groovy

pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                echo 'Hello, world!'
                sh 'make hello' 
            }
        }
        stage('Test'){
            steps {
                echo 'Test'
                sh './hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy!'
            }
        }
    }
}
