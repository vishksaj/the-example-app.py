pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'make build dt=$(date "+%d/%m/%Y%H:%M:%S")'
            }
        }
    }
}
