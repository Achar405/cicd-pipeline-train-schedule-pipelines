pipeline {
  agent any 
  stages {
    stage ('Build') {
      steps {
        echo "Hi I am Pipelining"
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
 }
