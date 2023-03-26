pipeline {
  agent docker {
    label 'docker'
  }
  stages {
    stage('Execute') {
      steps {
        sh script.sh
      }
    }
  }
}