pipeline {
  agent any
  stages {
    stage 'build'
    {
      echo 'Build automation'
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
  
}
