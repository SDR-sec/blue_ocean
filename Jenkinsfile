pipeline {
  agent {
    node {
      label 'docker'
    }

  }
  stages {
    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            echo 'Cookies are goated.'
          }
        }

        stage('Test2') {
          steps {
            echo 'Running'
          }
        }

      }
    }

    stage('Test3 - Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Clean Up - Barney Style') {
      steps {
        echo 'Cleaning'
      }
    }

  }
}