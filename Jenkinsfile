pipeline {
    agent any
    stages {
        stage('Demo Stage'){
            steps {
                sh "ls"
                sh "pwd"
                // sh "mkdir pipeline_test"
                // sh "cd pipeline_test"
                sh "ls"
            }
        }
         stage('Build Stage'){
             steps {
                 sh "chmod +x jenkins1/scrip.sh"
                 sh "jenkins1/scrip.sh"
           }
         }
    }
}
