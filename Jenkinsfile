pipeline {
    agent any
    stages {
        stage("test") {
            steps {
                sh '''
                    echo "this is my first command"
                '''
                sh '''
                    echo "By the way this is our second command testing"
                    df -kh
                '''
            }
        }
    }
} 
