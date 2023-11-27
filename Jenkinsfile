pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        git(url: 'https://github.com/ABDELRAHMAN1499/test.git', branch: 'master')
      }
    }

    stage('test') {
      steps {
        sh 'cat test'
      }
    }

  }
}