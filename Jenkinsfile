pipeline {
  agent {
    docker {
      image 'golang'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'sh \'go version\''
      }
    }

  }
}