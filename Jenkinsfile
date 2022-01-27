pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando compilación...'
        sh 'mvn clean install'
        echo 'Finalizada'
      }
    }

  }
}