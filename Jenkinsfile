pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        git(branch: 'main', url: 'https://github.com/tamartayar/test.git')
      }
    }

    stage('build') {
      steps {
        sleep 5
      }
    }

  }
}