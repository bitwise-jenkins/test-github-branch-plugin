pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        echo 'BUILD_ID: ${BUILD_ID}'
        echo 'GIT_COMMIT: ${GIT_COMMIT}'
        echo 'GIT_PREVIOUS_COMMIT: ${GIT_PREVIOUS_COMMIT}'
        echo 'Hello 0d'
        echo 'Hello 2'
        echo 'Hello 5'
      }
    }
    stage('test') {
      steps {
        echo 'Hello 1'
        sleep (30)
      }
    }
  }
}