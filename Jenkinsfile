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
            sh test.sh
            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
