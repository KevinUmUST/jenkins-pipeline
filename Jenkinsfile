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
                sh 'echo "hello"' 
            }
        }
        stage('CreateInstance'){
            steps{
                sh 'echo "world"'
            }
        }
    }
}
