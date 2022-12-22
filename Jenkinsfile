pipeline {
    agent any
    tools {
        nodejs '18.12.1'
    }
    stages {
        stage('node') {
            steps {
                sh 'node -v'
            }
            steps {
                sh 'ls -la'
            }
        }
    }
}