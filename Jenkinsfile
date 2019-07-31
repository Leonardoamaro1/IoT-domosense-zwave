pipeline {
  agent any
  stages {
    stage('make') {
      parallel {
        stage('make') {
          steps {
            echo 'Done'
          }
        }
        stage('check') {
          steps {
            echo 'kabli'
            echo 'ddd'
          }
        }
      }
    }
  }
}