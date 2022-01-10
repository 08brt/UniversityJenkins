pipeline {
  agent any
  stages {
    stage('Code Project') {
      steps {
        bat 'Jenkins.java'
      }
    }

    stage('Test Code') {
      steps {
        build 'BMW'
      }
    }

  }
}