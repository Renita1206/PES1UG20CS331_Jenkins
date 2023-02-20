pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
            }
        }
        stage('Test') {
            
        }
        stage('Deploy') {
            steps {
                echo "Deployement Successfull"
            }
        }
    }
    
    post {
        failure {
            echo "Pipeline failed"
        }
    }
}
