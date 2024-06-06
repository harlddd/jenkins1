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
        // stage('Build Stage'){
        //     steps {
        //         sh "chmod +x jenkins1/Script.sh"
        //         sh "jenkins1/Script.sh"
        //     }
        // }
        // stage('Docker Tools'){
        //     steps {
        //         // Docker installed on the machine Jenkins is installed
        //         // Installing docker, adding Jenkins to user group
        //         // Login as Jenkins with sudo su jenkins, check if Jenkins can run Docker `docker run --rm hello-world`
        //         sh "docker run -d -p 80:80 nginx"
        //         sh "curl localhost"
        //         sh "exit 1"
        //     }
        // }
        stage('Task 1 job'){
            steps {
                sh "ls"
                sh "chmod +x task1/build_script.sh"
                sh "./task1/build_script.sh"
                sh "curl localhost"
            }
        }
    }
    post { 
        always { 
            cleanWs()
        }
    }
}
