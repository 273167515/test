pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            sleep(time: 10, unit: 'SECONDS')
          }
        }
        stage('ssaf') {
          steps {
            sleep 10
          }
        }
      }
    }
    stage('pro') {
      steps {
        sh '''#!/bion/bash
echo ass'''
      }
    }
  }
}