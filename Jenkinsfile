pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando compilaci�n...'
        sh 'mvn clean install'
        echo 'Finalizada'
      }
    }

  }
}