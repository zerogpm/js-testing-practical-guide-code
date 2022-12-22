// tools {
//         nodejs '18.12.1'
// }   
// node {
//     stage('clone') {
//         git branch: '02-setup', credentialsId: 'Github', url: 'https://github.com/zerogpm/js-testing-practical-guide-code.git'
//     }
//     stage('list directory') {
//         if (isUnix()) {
//             sh 'ls -la'
//         } else {
//             bat 'dir'
//         }
//     }
//     stage('testing') {
//         sh 'node -v'
//     }
// }
pipeline {
    agent any
    tools {
        nodejs '18.12.1'
    }   

    stages {
        stage('clone') {
            git branch: '02-setup', credentialsId: 'Github', url: 'https://github.com/zerogpm/js-testing-practical-guide-code.git'
        }
        stage('node') {
            steps {
                sh 'node -v'
            }
        }
    }
}