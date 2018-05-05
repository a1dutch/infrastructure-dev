@Library('pipeline@master') _
pipeline {
  agent { label 'helm' }
  stages {
    stage('Deploy') {
      steps {
        deploy(namespace: 'dev')
      }
    }
  }
}
