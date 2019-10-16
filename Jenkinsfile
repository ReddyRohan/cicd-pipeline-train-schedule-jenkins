pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running Build automation'
        sh './gradlew build --no-dameon'
        archiveArtifacts artifact: 'dist/trainSchedule.zip'
      }
    }
   }
 }
