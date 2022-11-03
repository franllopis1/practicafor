pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        script {
          for (i) in `cat release.yaml`
          do
            echo "La verson $i"
          done
        }
      }
    }
  }
}