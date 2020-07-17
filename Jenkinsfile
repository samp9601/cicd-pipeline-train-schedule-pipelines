pipeline {
agent any
stages{
stage ('build'){
   echo 'running build automation'
   sh './gradlew build --no-daemon'
   archiveartifacts artifacts: 'dist/trainschedule.zip'
    }
   }
  }
 }
