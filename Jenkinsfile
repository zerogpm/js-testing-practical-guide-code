node {
    stage('clone') {
        git branch: '02-setup', credentialsId: 'Github', url: 'https://github.com/zerogpm/js-testing-practical-guide-code.git'
    }
    stage('list directory') {
        if (isUnix()) {
            sh 'ls -la'
        } else {
            bat 'dir'
        }
    }
    stage('testing') {
        sh 'cd ~'
        sh 'ls -la'
    }
}