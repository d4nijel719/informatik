pipeline {
  agent any
  stages {
    stage('Hallo') {
      steps {
        sh 'npm install'
        sh 'npm run scss:prod'
        sh 'npm run script:prod'
      }
    }

  }
}