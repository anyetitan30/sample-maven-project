stages {
  stage('maven install') {
    steps {
        withMaven(globalMavenSettingsConfig: '', jdk: '', maven: 'maven-test', mavenSettingsConfig: '', traceability: true) {
    sh "mvn clean install"
}
      
    }
  }

}
