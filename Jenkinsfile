pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'mvn compile'
      }
    }
    stage('load') {
      steps {
        libraryResource 'https://github.com/dev23kmr/GitRepot.git'
      }
    }
  }
}