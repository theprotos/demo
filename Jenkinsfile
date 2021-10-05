pipeline {
  agent {
    node {
      label 'linux'
    }

  }
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build message'
          }
        }

        stage('Test') {
          steps {
            echo 'Test stage'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }

  }
}