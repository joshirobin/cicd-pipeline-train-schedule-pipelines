pipeline {
  agent any
    stage {
      stage('Build'){
        steps {
        echo 'Running Build automation'
        sh'./gradlww build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
         }      
       }
    }      
}
