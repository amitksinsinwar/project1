pipeline {
  agent {
    any {
      label 'linux'

    }
  }
  stages {
    stage('Execute') {
      steps {
        sh './script.sh'
      }
    }
  }
}