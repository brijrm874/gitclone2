pipeline {
    agent any
    stages {
        stage('Pull Image') {
            steps {
                sh 'sudo docker pull brijrm874/rajdemo1:v1'
            }
        }
        stage('Run Container') {
            steps {
                sh 'sudo docker run --rm brijrm874/rajdemo1:v1'
            }
        }
    }
}
