pipeline {
  agent any
  stages {
    stage('Install powerkit') {
      steps {
        bat 'rc = command "echo y | ${toolbelt}sfdx plugins:install sfpowerkit'
      }
    }

  }
}