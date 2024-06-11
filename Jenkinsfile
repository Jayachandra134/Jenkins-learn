pipeline {
    agent {
        label = 'AGENT-1'
    }
    stages {
        stage('Build') {
            steps {
                echo "this is my first build stage"
            }
        }
        stage('Test') {
            steps {
                echo "this is my second test stage" 
            }
        }
        stage('Deploy') {
            steps {
                echo "this is my third deploy stage"
            }
        }
    }
}