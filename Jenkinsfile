pipeline {
  agent {
    label 'docker'
  }
  stages {
    stage('build') {
      agent any
      steps {
        sh 'mvn --version'
      }
    }

  }
}