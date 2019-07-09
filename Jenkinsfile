pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        sh 'sudo apt-get install python-setuptools -y'
        sh 'pip install -r requirements.txt'
        sh 'make run'
      }
    }
  }
}
