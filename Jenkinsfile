pipeline {
  agent any
  stages {
    stage('Git Logs') {
      steps {
        sh 'git log --pretty=oneline'
      }
    }

    stage('SSH Connection') {
      steps {
        sh '''cd /var/www/html/Arsha
ls'''
      }
    }

  }
}