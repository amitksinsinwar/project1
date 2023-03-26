pipeline {
  agent {
    docker {
      label 'docker'
      image 'praqma/network-multitool'
    }
  }
  stages {
    stage('Execute') {
      steps {
        sh 'script.sh'
      }
    }
  }
}