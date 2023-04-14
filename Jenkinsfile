pipeline {
  agent any
  stages {
    stage ('Run Docker Compose') {
      steps{
        sh 'sudo -S docker-compose up -d'
      }
    }
  }
}
