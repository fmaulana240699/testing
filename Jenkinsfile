pipeline {
  agent any
  stages {
    stage('Test Cloning') {
      steps {
        git(url: 'https://github.com/fmaulana240699/testing.git', branch: 'master')
      }
    }

    stage('LS') {
      steps {
        sh 'ls -l'
      }
    }

  }
}