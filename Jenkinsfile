pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando compilaciÃ³n...'
      }
    }

    stage('CAMBIO DE RAMA') {
      parallel {
        stage('CAMBIO DE RAMA') {
          steps {
            sh 'git checkout answer4'
          }
        }

        stage('TEXTO') {
          steps {
            echo 'Cambio de rama'
          }
        }

      }
    }

    stage('COMPILACIÓN') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}