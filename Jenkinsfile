pipeline {
  agent {
    dockerfile {
      filename './'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
  }
}