properties([pipelineTriggers([githubPush()])])

node('linux') {
    git url: 'https://github.com/KevinUmUST/jenkins-pipeline.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}

pipeline {
    agent any
    stages {
        stage('GetInstances') {
            steps {
                sh "aws ec2 describe-instances --region us-east-1"
          }
        }
        stage('CreateInstance'){
            steps{
                sh 'echo "world"'
            }
        }
    }
}
