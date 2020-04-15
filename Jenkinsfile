pipeline {
   agent any 
      stages {
         stage ('Build') {
           steps {
             echo 'Running build automation'
             sh './gradlew --no daemon' 
             ArchiveArtifacts artifacts: 'dist/trainSchedule.zip'
           }
         }
      }
}   
   
