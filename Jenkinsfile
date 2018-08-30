pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('say hello') {
      steps {
        echo 'Hello!'
        sh 'java -version'
      }
    }
  }
}