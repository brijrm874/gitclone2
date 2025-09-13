pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
                sh 'ls -l'
            }
        }
        stage('Test') {
            steps {
                echo "Running tests for ${env.BRANCH_NAME}"
            }
        }
    }
}
