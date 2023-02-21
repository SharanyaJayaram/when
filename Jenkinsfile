pipeline {

  agent any
   tools {
        maven 'apache-maven-3.0.1'
    }

  options {

     timestamps ()  
     skipDefaultCheckout true
     buildDiscarder(logRotator(numToKeepStr: '2'))
     }

  stages {

    stage('To check java version') {

      steps {

        sh 'mvn --version'

      }

    }

  }
}
