pipeline {
  agent any
  stages {
    stage('practica for') {
      steps {
        sh '''
        for i in `cat release.yaml`
        do
          echo La version `cut -d " " -f1 $i` es `cut -d " " -f2 $i`
        done'''
      }
    }
  }
}