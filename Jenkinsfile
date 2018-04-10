pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('maven1') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}