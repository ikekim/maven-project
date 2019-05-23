pipeline {
    agent any
 
    stages {
        stage('Build/ Unit Testing') {
            steps {
                sh 'echo build'
                sh label: '', script: 'node -v'
                sh label: '', script: 'npm -v'
                sh label: '', script: 'echo "build 15"'
            }
        }
   
    }
    options {
        branchTearDownExecutor jobName:'MyFolderName~/teardown-job'
            }
}