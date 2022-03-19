pipeline {
  agent any
  tools { 
      maven '/usr/local/Cellar/maven/3.8.5' 
      jdk '/Library/Java/JavaVirtualMachines/jdk-11.0.13.jdk/Contents/Home' 
  }
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
        }
      }
  }
}    
