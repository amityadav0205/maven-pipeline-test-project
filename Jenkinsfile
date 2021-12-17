pipeline{
 agent any 
 stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'Maven 3.8.4') {
    sh 'mvn clean install'
}
    }
  }

}

}
