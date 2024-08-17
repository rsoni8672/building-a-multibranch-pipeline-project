pipeline {
    agent any
    tools {
        nodejs "NODE-22"
    }
    stages {
        stage('Build') { 
            steps {
                echo 'node version is'
                sh 'node -v'
                sh 'npm install' 
            }
        }
    }
}
