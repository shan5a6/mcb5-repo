pipeline {
  /*agent server1/docker/kubernetes/any*/
  agent any 
  stages {
    stage('git checkout') {
      steps {
        script {
          File file = new File("/opt/mydata.txt")
          def lines = file.readLines()
          //["Hi i am line1","Hi i am line2","Hi i am line3"]
          println "Lines\n ${lines}"
          for (line in lines) {
            println "myline is ${line}"
          }
        }
      }
    }
  } 
}
