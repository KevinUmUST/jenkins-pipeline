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
          sh 'echo hello' 
        }
        stage('CreateInstance'){
          sh 'echo world'
        }
    }
}
