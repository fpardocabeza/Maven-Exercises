pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando compilaci√≥n...'
      }
    }

    stage('CAMBIO DE RAMA') {
      parallel {
        stage('CAMBIO DE RAMA') {
          steps {
            sh 'git checkout answer 4'
          }
        }

        stage('TEXTO') {
          steps {
            echo 'Cambio de rama'
          }
        }

      }
    }

    stage('COMPILACI”N') {
      steps {
        sh 'mvn clean install'
        echo 'Chachi'
      }
    }

  }
}