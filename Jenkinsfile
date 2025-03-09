pipeline {
  agent any
  stages {
    stage('chechOut') {
      steps {
        echo 'this stage completed '
      }
    }

    stage('build') {
      steps {
        echo 'build stage completed '
      }
    }

    stage('test') {
      steps {
        echo 'test stage completed '
      }
    }

    stage('deploy') {
      steps {
        input(message: 'are you sure to deploy', ok: 'yes, I\'m sure')
        echo 'deploy stage completed '
      }
    }

  }
}