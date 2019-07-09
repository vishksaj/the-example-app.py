pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'pip install --user jenkins -r requirements.txt'
        sh 'make run'
      }
    }
  }
}
