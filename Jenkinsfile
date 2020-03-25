pipeline {
  agent {
    node {
      label 'android'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''cat /etc/issue.net
echo "$ANDROID"'''
        pwd()
      }
    }

  }
  environment {
    ANDROID = 'Yes'
  }
}