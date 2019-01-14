pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'gradle build '
        archiveArtifacts '1.0/build/libs/*.jar'
        bat 'gradle javadoc'
      }
    }
  }
}