@Library('pipeline@master')

pipeline {
  stages {
    agent { label 'helm' }
    steps {
      deploy(namespace: 'dev')
    }
  }
}
