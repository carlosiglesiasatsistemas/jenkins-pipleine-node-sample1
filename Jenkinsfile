pipeline {
    agent { docker { image 'node:lts-bullseye-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}