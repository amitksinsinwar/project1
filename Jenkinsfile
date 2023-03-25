pipeline {
  agent {
    docker {
      label 'docker'
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