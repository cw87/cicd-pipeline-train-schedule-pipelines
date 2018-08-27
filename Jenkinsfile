pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running Build Automation'
        sh './gradlew build'
        archiveArtifacts artifacts:'dist/trainSchedule.zip'
      }
    }
  } 
}
