pipeline{
  agent any
  
  stages {
  
    stage("Building"){
      steps{
        echo "This sis buildigng pipeline ! "
        sh './gradlew build --no-daemon '
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
    }
  }
}
