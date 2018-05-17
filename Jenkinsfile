@Library('pipeline@master') _
pipeline {
  agent { label 'helm' }
  stages {
    stage('Deploy') {
      steps {
        helmDeploy(namespace: 'dev')
      }
    }
  }
}
