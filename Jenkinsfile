pipeline {
  agent {
    docker {
      label 'linux'
      image 'busybox'
    }
  }
  stages {
    stage('Execute') {
      steps {
        sh script.sh
      }
    }
  }
}