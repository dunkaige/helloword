pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                echo 'this is a building....'
                sh 'npm --version'
            }
        }
    }
}