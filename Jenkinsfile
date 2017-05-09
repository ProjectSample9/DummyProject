pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        svn(url: 'http://192.168.2.144:8080/rsaaegapp/', poll: true)
      }
    }
  }
}