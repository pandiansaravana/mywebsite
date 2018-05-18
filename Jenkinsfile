pipeline {
  agent any
  stages {
    stage('merge with master') {
      steps {
        bat(script: 'git merge develop', returnStatus: true, returnStdout: true)
      }
    }
  }
}