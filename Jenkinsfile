pipeline {
  agent any
  stages {
    stage('practica for') {
      steps {
        sh '''
        for i in `cat release.yaml`
        do
          echo $i
        done
        '''
      }
    }
  }
}