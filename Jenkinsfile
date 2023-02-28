pipeline {
  agent any
  stages {
    
    stage('Deploy Standalone') {
      steps {
        bat 'mvn clean deploy -DmuleDeploy'
      }
    }
   
  }
}