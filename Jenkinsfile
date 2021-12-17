pipeline{
 agent any 
 stages {
  stage('maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'Maven 3.8.4', mavenSettingsConfig: 'null') {
    sh 'mvn clean install'
}
    }
  }

}

}
