pipeline {
  agent any
  stages {
    stage('practica for') {
      steps {
        sh '''
        for i in `cat release.yaml`
        do
          echo "La version $(echo "$i" | cut -d ":" -f1) es$(echo "$i" | cut -d ":" -f2)"
        done
        '''
      }
    }
  }
}