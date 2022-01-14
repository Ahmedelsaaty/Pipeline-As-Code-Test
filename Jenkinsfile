pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build completed'
        timeout(time: 5, unit: 'NANOSECONDS') {
        sh 'sleep 2'
}
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