Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:6.3' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
        stage('test') {
            steps {
                sh 'npm run test'
            }
        }
    }
}
