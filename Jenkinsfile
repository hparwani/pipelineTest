library 'SharedLibs'

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
    stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
     }
    
  }
}
