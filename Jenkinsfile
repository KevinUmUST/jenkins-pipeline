properties([pipelineTriggers([githubPush()])])

node('linux') {
    git url: 'https://github.com/KevinUmUST/jenkins-pipeline.git', branch: 'master'
    stage('Test') {
        sh "env"
    }
}

pipeline {
    stages {

        stage('GetInstances') {
        
        }
        stage('CreateInstance'){

        }
    }
}
