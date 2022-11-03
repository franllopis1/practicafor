pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        sh 'for i in `cat release.yaml`
        do
          echo La verson $i 
        done'
      }
    }
  }
}