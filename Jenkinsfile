pipeline {
  agent any
  stages {
    stage('developing') {
      steps {
        echo 'developer writing the code'
      }
    }

    stage('code pull') {
      steps {
        echo 'Taking the code from github'
      }
    }

    stage('build') {
      steps {
        echo 'Building the code by using maven'
      }
    }

    stage('testing') {
      steps {
        echo 'testing the code'
      }
    }

    stage('release') {
      steps {
        echo 'release the code'
      }
    }

  }
}