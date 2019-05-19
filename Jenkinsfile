pipeline {
  agent any
    stages {
     stage ('Build') {
       steps {
          echo 'Running build auotmation'
          sh './gradlew build --no-daemon'
          archiveArtifacts artifacts: 'dist/trainSchedule.zip'
     }
   }
 }
}
