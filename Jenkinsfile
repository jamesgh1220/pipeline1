pipeline {
  agent any
  stages {
    stage('Paso 1') {
      parallel {
        stage('Paso 1') {
          steps {
            build 'ProyectoMaven'
          }
        }

        stage('Paso 2') {
          steps {
            build 'JOB1'
          }
        }

      }
    }

    stage('Paso 3') {
      steps {
        build 'JOB3'
      }
    }

  }
}