pipeline {

  agent any
   tools {
        jdk 'jdk11'
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
