pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building Now.....'
      }
    }
    stage('Testing Firefox') {
      parallel {
        stage('Testing Firefox') {
          steps {
            sh 'echo "Testing Firefox...!!!"'
          }
        }
        stage('Testing Chrome') {
          steps {
            sh 'echo "Testing Firefox...!!!"'
          }
        }
        stage('Testing IE') {
          steps {
            sh 'echo "Testing Firefox...!!!"'
          }
        }
      }
    }
    stage('Deployment') {
      steps {
        sh 'echo "Deploying now...!!!"'
      }
    }
  }
}