pipeline {
  agent {
    docker {
      image 'ubuntu:bionic'
    }

  }
  stages {
    stage('Build') {
      steps {
        fileExists 'Dockerfile'
      }
    }

  }
}