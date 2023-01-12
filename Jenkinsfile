pipeline {
    agent {
        tools {nodejs "node"}
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}