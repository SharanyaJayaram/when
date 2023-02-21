pipeline {

  agent any
  options {

     timestamps ()  
     skipDefaultCheckout true
     buildDiscarder(logRotator(numToKeepStr: '2'))
     }

  stages {

    stage('Add a readme file') {

      steps {

        echo "Trying out multibranch pipeline" >> README.md

      }

    }

  }
}
