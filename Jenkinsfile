pipeline{
    agent any
    stages{
      stage('build'){
        steps{
            echo 'Welcome to Train Schedule Build Process'
            sh './gradew build'
            archiveArtifacts artifacts: 'dist/trainSchedule.zip' 
        }
      }
    }
  }
