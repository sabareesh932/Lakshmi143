pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/sabareesh932/Lakshmi143.git', branch: 'master', poll: true)
      }
    }
    stage('describe') {
      steps {
        echo 'hai this is a cocean project.'
      }
    }
  }
}