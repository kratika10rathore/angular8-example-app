pipeline {
  agent any
  stages {
    stage('Update') {
      steps {
        bat 'npm update'
        bat 'npm install'
      }
    }

  }
}