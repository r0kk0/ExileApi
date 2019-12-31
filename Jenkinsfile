pipeline {
  agent {
    node {
      label 'visual_studio'
    }

  }
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/r0kk0/ExileApi', branch: 'master')
      }
    }

  }
}