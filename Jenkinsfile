pipeline {
  agent {
    node {
      label 'w1'
    }

  }
  stages {
    stage('scmrepo') {
      steps {
        sh 'echo "hey baby"'
        sh 'echo "hi hello"'
      }
    }

    stage('buildtriggred') {
      steps {
        sh 'echo "initiated buildv4"'
      }
    }

  }
}
