pipeline {

  agent any
   tools {
        jdk 'default-jdk'
    }

  options {

     timestamps ()
     timeout(time: 5, unit: 'MINUTES')   
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
