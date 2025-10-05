pipeline {
    agent any
    stages {
        stage('Pull Image') {
            steps {
                sh 'docker pull brijrm874/rajdemo1:v1'
            }
        }
        stage('Run Container') {
            steps {
                sh 'docker run --name test-runner brijrm874/rajdemo1:v1'
            }
        }
    }
}
