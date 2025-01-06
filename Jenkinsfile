pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
withMaven ( maven: 'maven-test') {
}        sh 'mvn clean install'

      }
    }

  }
}
