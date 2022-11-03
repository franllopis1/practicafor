pipeline {
  agent any
  stages {
    stage('practica') {
      steps {
        script {
          for (1) in `cat release.yaml`
          do
            echo "La verson $i"
          done
        }
      }
    }
  }
}