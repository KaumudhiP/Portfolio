pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'npm i'
        bat 'npm run dev'
      }
    }

    stage('Test') {
      steps {
        bat 'npm run dev'
      }
    }

  }
}