pipeline {
  agent any
    stages {
     stage ('Build') {
       steps {
          echo 'Running build auotmation'
          sh './gradlew build --no-daemon'
          archiveArttifact artifacts: 'dist/trainSchedule.zip'
     }
   }
 }
}
