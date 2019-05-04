pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "hello testing"'
      }
    }
    stage('Deploy Dev') {
      steps {
        echo 'Deploy dev'
      }
    }
    stage('deploy Prod') {
      steps {
        echo 'Deploy prof'
        waitUntil()
      }
    }
  }
}