pipeline {
  agent any
  stages {
    stage('chuck') {
      steps {
        retry(count: 2) {
          chuckNorris()
        }

        echo 'aahsdsads'
      }
    }

    stage('sleep') {
      steps {
        sleep 1
        echo 'aahsdsads'
      }
    }

  }
}