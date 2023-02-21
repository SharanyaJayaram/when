pipeline {

  agent any
   tools {
        jdk 'jdk9'
    }

  options {

     timestamps ()  
     skipDefaultCheckout true
     buildDiscarder(logRotator(numToKeepStr: '2'))
     }

  stages {

    stage('To check java version') {

      steps {

        sh 'java --version'

      }

    }

  }
}
