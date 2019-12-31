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

    stage('checkout plugins') {
      steps {
        git 'https://github.com/r0kk0/ExileApiPlugins.git'
      }
    }

  }
}