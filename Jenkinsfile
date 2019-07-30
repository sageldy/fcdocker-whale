pipeline {
  agent {
        docker {
            label 'slave-docker'
            image 'jnlp-slave'
      }
  }
  stages {
    stage('init') {
      steps {
        echo 'hi'
        echo 'docker ps'
      }
    }
  }
}
