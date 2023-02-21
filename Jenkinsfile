pipeline {

  agent any
  options {

     timestamps ()  
     skipDefaultCheckout true
     buildDiscarder(logRotator(numToKeepStr: '2'))
     }

  stages {

    stage('Main file') {

      steps {

        echo "Trying out multibranch pipeline" >> main.txt

      }

    }

  }
}
