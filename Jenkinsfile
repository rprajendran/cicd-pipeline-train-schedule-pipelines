pipeline {
  agent any
  stages {
    stage ('build') {
      steps {
        echo 'Build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
