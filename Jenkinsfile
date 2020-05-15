pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            bat 'npm i'
          }
        }

        stage('buid') {
          steps {
            bat 'npm build'
          }
        }

      }
    }

    stage('Test') {
      steps {
        bat 'npm test'
      }
    }

  }
}