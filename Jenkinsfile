pipeline {
  agent any
  stages {
    stage('email') {
      steps {
        emailext(subject: 'this is itest', body: 'boady', attachLog: true, replyTo: 'me@me.com', to: 'me@me.com')
      }
    }
  }
}