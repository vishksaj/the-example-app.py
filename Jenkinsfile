pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'pip install -r requirements.txt --user root'
        sh 'make run'
      }
    }
  }
}
