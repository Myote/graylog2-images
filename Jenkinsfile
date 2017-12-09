pipeline {
  agent any
  stages {
    stage('Stage1') {
      steps {
        pwd()
        bat(script: 'echo toto', returnStatus: true, returnStdout: true)
      }
    }
  }
}