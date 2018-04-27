pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn clean package'
        echo 'build is created here'
      }
    }
    stage('test') {
      steps {
        echo 'testing is done here'
      }
    }
    stage('deployment') {
      steps {
        echo 'deployment is done here'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_144'
    MAVEN_HOME = 'C:\\Program Files (x86)\\apache-maven-3.5.3'
  }
}