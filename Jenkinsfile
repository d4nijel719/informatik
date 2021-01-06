pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'javac HelloWorld.java'
      }
    }

    stage('ausführen') {
      steps {
        sh 'java HelloWorld.class'
      }
    }

  }
}