pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Another try'
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
