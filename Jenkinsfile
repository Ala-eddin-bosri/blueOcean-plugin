pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build completed'
      }
    }

    stage('test stages') {
      parallel {
        stage('test stages') {
          steps {
            echo 'enter to test stages'
          }
        }

        stage('test1') {
          steps {
            echo 'running test1 ...'
          }
        }

        stage('test2') {
          steps {
            echo 'running test2 ...'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploy completed'
      }
    }

  }
}