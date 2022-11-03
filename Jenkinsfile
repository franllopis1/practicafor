pipeline {
  agent any
  stages {
    stage('practica for') {
      steps {
        sh '''for i in `cut -d " " -f1 release.yaml`
        do
          echo La version $i $e
        done'''
      }
    }
  }
}