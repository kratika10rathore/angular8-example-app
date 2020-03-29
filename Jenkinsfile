pipeline {
  agent any
  stages {
    stage('Install/Update') {
      parallel {
        stage('Update') {
          steps {
            bat 'npm update'
          }
        }

        stage('Install') {
          steps {
            bat 'npm install'
          }
        }

      }
    }

  }
}