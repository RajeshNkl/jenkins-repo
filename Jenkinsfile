pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "stage-1"
                sh test.sh 
            }
        }
        stage('Test') { 
            steps {
            echo "stage-2"
            }
        }
        stage('Deploy') { 
            steps {
                echo "stage-3"
            }
        }
    }
}
