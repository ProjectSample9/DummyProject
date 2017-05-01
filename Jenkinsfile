pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/ProjectSample9/DummyProject.git', branch: 'master', poll: true)
      }
    }
  }
}