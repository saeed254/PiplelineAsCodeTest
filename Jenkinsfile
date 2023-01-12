pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed ......'
        timeout(time: 5, unit: 'NANOSECONDS') {
          sh 'sleep 10'
          }
      }
    }
    stage('Test') {
      steps {
        echo 'Testing Completed ......'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment Completed ......'
      }
    }
  }
}