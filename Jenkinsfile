pipeline {
  agent {
    node {
      label 'android'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'cat /etc/issue.net'
      }
    }

  }
  environment {
    ANDROID = 'Yes'
  }
}