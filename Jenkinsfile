pipeline {
  stages {
    stage ('build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifact: 'dist/trainschedule.zip'
      }
    }
  }
}
