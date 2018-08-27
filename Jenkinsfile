pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running Build Automation'
        sh './gradlew build'
        archieveArtifacts dist/train-schedult
      }
    }
  } 
}
