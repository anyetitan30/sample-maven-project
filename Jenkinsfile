pipeline {
    agent any 
    stages {
    stage('maven install') {
      steps {
withmaven (globalMavenSettingsConfig: '', jdk: '', maven: 'maven-test', mavenSettingsConfig: '', traceability: true) {
}        sh 'mvn clean install'

      }
    }

  }
}
