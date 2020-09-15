node {
  // stage is optional
  sh 'echo hello stageless sh step'
  echo 'hello stageless echo step'
  stage('first') {
    echo 'hello first stage'
  }
  stage('second') {
    sh 'echo hello second stage'
  }
}