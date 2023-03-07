pipeline {
  agent any
  stages {
    stage('shell-1') {
      steps {
        sh 'ls /tmp'
      }
    }

    stage('shell-2') {
      steps {
        sh 'cd /data/'
      }
    }

    stage('shell-3') {
      steps {
        sh 'cd /opt/apache-maven-3.8.7/bin'
      }
    }

  }
}