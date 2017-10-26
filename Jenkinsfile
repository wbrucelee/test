pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('1') {
          steps {
            echo 'begin'
          }
        }
        stage('2') {
          steps {
            sh 'echo "hello"'
          }
        }
      }
    }
  }
}