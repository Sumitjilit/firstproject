pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        echo 'code is fetche from repo'
      }
    }
    stage('Built') {
      steps {
        bat 'mvn clean package'
        echo 'Build the code'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\java\\jdk1.8.0_144'
    MAVEN_HOME = 'F:\\apache-maven-3.5.2'
  }
}