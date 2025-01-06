pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
with maven (globalMavenSettingsConfig: '', jdk: '', maven: 'maven-test', mavenSettingsConfig: '', traceability: true) {
}        sh 'mvn clean install'

      }
    }

  }
}
