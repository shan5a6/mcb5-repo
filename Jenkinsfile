pipeline {
  agent any //any, slave1, docker, kubernetes .. 
  stages {
    stage('working with conditions') {
      steps {
        script {
          a=100
          b=20
          if(a>b) {
            println "a is big ${a}"
          }
          else {
            println "b is big ${b}"
          }
        }
      }
    }
  }
}
