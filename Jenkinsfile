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
    stage('Test') {
      steps {
        sh 'cd tests; ./tests.pl'
      }
    }
  }
}
