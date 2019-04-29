pipeline {
    agent any

    stages {
        stage('Build/ Unit Testing') {
            steps {
                sh 'echo build'
                sh label: '', script: 'node -v'
                sh label: '', script: 'npm -v'
                sh label: '', script: 'echo "nomnomnom"'
            }
        }
  
    } 
}