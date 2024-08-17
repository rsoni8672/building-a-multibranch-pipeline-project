pipeline {
    agent any
    tools {
        node "NODE-22"
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
