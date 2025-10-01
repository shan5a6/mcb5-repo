pipeline {
  agent any //any, slave1, docker, kubernetes .. 
  environment {
    JAVA_HOME = "/opt/bin/java"
  }
  parameters {
    choice choices: ['dev', 'prod'], description: 'Select the environment', name: 'ENV'
  }  
  stages {
    stage('working with variables') {
      steps {
        script {
          batchno=5
          println "my batchno is ${batchno}"
          println "my java home variable value is ${env.JAVA_HOME}"
          println "my selected environment is ${params.ENV}"
        }
      }
    }
  }
}
