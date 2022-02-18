pipeline{
agent any 
  stages{
    stage('Build') {
      steps{
      echo 'Hello Joey'
        sh './gradlew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
