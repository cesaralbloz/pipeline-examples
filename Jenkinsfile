pipeline {
  agent any
  stages {
    stage('Prueba') {
      parallel {
        stage('Prueba') {
          steps {
            sh 'echo "Hola mundo!!!"'
          }
        }
        stage('') {
          steps {
            sh 'echo "Buenos dias"'
          }
        }
      }
    }
  }
}