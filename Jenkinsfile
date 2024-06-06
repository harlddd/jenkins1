pipeline{
    agent {
        label "worker"
    }
    stages {
        stage("make directory"){
            steps{
                sh "mkdir ~/jenkins-pipline"
            }
        }
        stage("add some files"){
            steps{
            sh "touch ~/jenkins-pipeline/file1.txt"
            sh "ls -al"
            }
        }
    }
}
