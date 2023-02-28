pipeline {
  agent any
  stages {
    
    stage('Deploy Standalone') {
      steps {
        sh 'mvn clean deploy -DmuleDeploy'
      }
    }
   
  }
}