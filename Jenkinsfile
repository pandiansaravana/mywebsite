pipeline {
  agent any
  stages {
    stage('Deploy') {
      steps {
        bat(script: 'cp index.html C:\\pandian_website', returnStatus: true, returnStdout: true)
      }
    }
  }
}