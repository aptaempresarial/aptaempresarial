pipeline {
  agent {
    docker {
      image 'jekyll/builder'
    }

  }
  stages {
    stage('error') {
      steps {
        sh 'jekyll build'
      }
    }

  }
}