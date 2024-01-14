pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'apt-get install python3.7.9'
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
