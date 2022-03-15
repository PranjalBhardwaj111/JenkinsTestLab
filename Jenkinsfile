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
          sh 'mvn test'
        }
      }
      stage('Build') {
        steps{
          echo 'Building jar files...'
          sh 'mvn package'
        }
      }
  }
}    
