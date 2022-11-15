pipeline {
    agent any
  stages {
    stage {'Build'} {
      steps {
        echo 'Runnning Build Automation'
        sh './gradelew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainsSchedule.zip'
      }
    }
  }
}
