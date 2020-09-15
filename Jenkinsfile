pipeline {
  agent any
  stages {
    // stage is optional
    
    stage('first') {
      steps {
        sh 'echo hello stageless sh step'
        echo 'hello stageless echo step'
        echo 'hello first stage'
      }
    }
    stage('second') {
      steps {
        sh 'echo hello second stage'
      }
    }
  }
}