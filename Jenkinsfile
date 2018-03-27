pipeline {
  agent {
    docker {
      image 'ubuntu'
    }
  }
  stages {
    stage('Build') {
      steps {
        sh './easybutton-build.sh'
      }
    }
  }
}
