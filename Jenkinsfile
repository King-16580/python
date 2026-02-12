pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            sh 'echo "aaa"'
          }
        }

        stage('test') {
          steps {
            echo 'abc'
          }
        }

      }
    }

  }
}