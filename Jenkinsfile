def myfn() {
  println "welcome to functions"
}
def myadd(a,b) {
  sum = a+b
  println "sum of ${a} and ${b} is ${sum}"
}
pipeline {
  agent any //any, slave1, docker, kubernetes .. 
  stages {
    stage('working with loops') {
      steps {
        script {
          myfn()
          myadd(100,200)
          myadd(400,500)
        }
      }
    }
  }
}
