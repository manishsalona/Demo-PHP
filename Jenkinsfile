pipeline {
  agent any
  stages {
    stage ('Run Docker Compose on EC2') {
      steps{
        sh 'sudo -S docker-compose up -d'
      }
    }
  }
}
