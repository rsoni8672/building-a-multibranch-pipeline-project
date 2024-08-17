pipeline {
    agent any
    tools {
        nodejs "NODE-22"
    }
    stages {
        stage('Build') { 
            steps {
                echo 'node version is'
                bat 'npm install' 
                bat 'npm run build'
            }
        }
    }
}
