pipeline {
  agent any
  environment{
       PATH= "C:/Program Files/apache-maven-3.6.3-bin/apache-maven-3.6.3:$PATH"
    }
  stages 
    {
    stage('Clean') {
      steps {
        sh "mvn clean"
      }
    }
    stage('Compile') {
      steps {
        sh "mvn compile"
      }
    }
    stage('Test') {
      steps {
        sh "mvn test"
      }
    }
  }
}
