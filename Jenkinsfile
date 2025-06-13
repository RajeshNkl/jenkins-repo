pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
             sh '''#!/bin/bash
                  free -h
           '''          
          }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
