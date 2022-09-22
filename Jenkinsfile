pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/idrees-pixako/Arsha', branch: 'main')
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