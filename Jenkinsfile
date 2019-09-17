pipeline {
  agent any
  stages {
    stage('Build'){
      steps {
              echo "Build Automation"
              sh './gradlew build --no-daemon'
              archiveArtifacts 'dist/trainSchedule.zip'
      }
    }
  }
}
