pipeline {
  agent any
  stages {
      stage('Testing'){
        steps{
          echo 'running Tests'
          echo 'Command 1'
        }
      }
      stage('Build') {
        steps{
          echo 'Building jar files...'
          echo 'Command 2'
          bat 'Python filename'
        }
      }
  }
}    
