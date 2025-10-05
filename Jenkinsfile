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
                sh 'docker run --rm brijrm874/rajdemo1:v1'
            }
        }
    }
}
