pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Show Commit') {
            steps {
                sh 'git log -1 --pretty=oneline'
            }
        }
    }
}
