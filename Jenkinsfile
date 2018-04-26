pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'build is done here'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }
    }
  }
  environment {
    MAVEN_HOME = 'C:\\Program Files (x86)\\apache-maven-3.5.3'
  }
}