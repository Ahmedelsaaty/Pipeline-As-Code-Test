pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
        timeout(time: 60, unit: 'NANOSECONDS') {
    // some block
}
      }
    }

    stage('Test') {
      steps {
        echo 'Test completed'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deployment completed'
      }
    }


  }
}