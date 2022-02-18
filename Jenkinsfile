pipeline{
agent any 
  stages{
    stage('Build') {
      steps{
      echo 'Hello Joey'
        sh './gradlew build'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
