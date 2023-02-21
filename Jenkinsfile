pipeline {

  agent any
  options {

     timestamps ()  
     skipDefaultCheckout true
     buildDiscarder(logRotator(numToKeepStr: '2'))
     }

  stages {

    stage('To check java version') {

      steps {
        script{
          sh 'java --version'
        }
      }
    }
    stage{
      steps{
      script{
        sh 'docker --version'
      }
      }
    }
  }
}
