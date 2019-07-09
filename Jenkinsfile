pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'apt-get install python-setuptools -y'
        sh 'pip install -r requirements.txt'
        sh 'make run'
      }
    }
  }
}
