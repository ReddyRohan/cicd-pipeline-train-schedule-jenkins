pipeline {
  agent any
  stages {
    stage ('Build'){
        echo 'Running Build automation'
        sh './gradlew build --no-dameon'
        archiveArtifacts artifact: 'dist/trainSchedule.zip'
    }
   }
 }
