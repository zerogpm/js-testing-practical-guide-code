pipeline {
    agent { label 'agent' }
    tools {
        nodejs '18.12.1'
    }
    stages {
        stage('node') {
            steps {
                sh 'node -v'
            }
        }
        stage('listing') {
            steps {
                sh 'npm -v'
            }
        }
    }
}