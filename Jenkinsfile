pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        powershell(script: 'echo "This is DEV"', returnStatus: true, returnStdout: true)
      }
    }
    stage('QA') {
      steps {
        powershell(script: 'echo "This is QA"', returnStatus: true, returnStdout: true)
      }
    }
  }
  environment {
    windows = 'true'
  }
}