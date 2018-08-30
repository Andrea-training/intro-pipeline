pipeline {
  agent {
    label 'jdk8'
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