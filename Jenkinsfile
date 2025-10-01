pipeline {
  agent any //any, slave1, docker, kubernetes .. 
  stages {
    stage('working with loops') {
      steps {
        script {
          list1=[10,20,30,40]
          for(i in list1) {
            println "my list value is ${i}"
          }

          for(i=1;i<=5;i++) {
            println "my i value  is ${i}"
          }

          j=10
          while(j<=15) {
            println "my j value is ${j}"
            j=j+1
          }
        }
      }
    }
  }
}
