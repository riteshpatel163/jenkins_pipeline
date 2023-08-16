pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh '''pwd
ls'''
          }
        }

        stage('test') {
          steps {
            echo 'hello'
          }
        }

      }
    }

    stage('test2t3') {
      parallel {
        stage('test2t3') {
          steps {
            echo 'wshdhfhj'
          }
        }

        stage('shfhf') {
          steps {
            sh 'sleep 2'
          }
        }

      }
    }

  }
}