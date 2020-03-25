pipeline {
  agent {
    node {
      label 'android'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh '''cat /etc/issue.net &&
echo "$ANDROID" &&
echo "$GIT_COMMIT"'''
      }
    }

  }
  environment {
    ANDROID = 'Yes'
  }
}