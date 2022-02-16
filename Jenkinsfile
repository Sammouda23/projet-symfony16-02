pipeline {
  agent any
  stages {
    stage('Build') {
      agent any
      steps {
        sh 'docker-compose up -d'
        sh 'docker exec app_name composer install'
      }
    }    
    
}}

