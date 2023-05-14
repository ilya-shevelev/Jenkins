pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/ilya-shevelev/Jenkins', branch: 'master')
      }
    }

    stage('Shell script') {
      steps {
        sh 'ls -la'
      }
    }

  }
}