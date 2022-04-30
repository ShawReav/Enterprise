pipeline {
  agent any
  stages {
    stage('scm') {
      steps {
        git 'https://github.com/ShawReav/Enterprise'
      }
    }

    stage('Install powerkit') {
      steps {
        sh 'install sfpowerkit'
      }
    }

  }
}