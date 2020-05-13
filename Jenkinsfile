pipeline {
   agent any

 stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat label: '', script: 'npm i'
                bat label: '', script: 'npm build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                bat label: '', script: 'npm test'
            }
        }
    }
}
