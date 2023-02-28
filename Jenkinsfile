pipeline {
  agent any
  stages {
    
    stage('Deploy Standalone') {
      steps {
        sh 'mvn clean deploy -DmuleDeploy -DaltDeploymentRepository=myinternalrepo::default::file:///C:/AAA/Work/Infometry/MuleSoft/Training/Utils/JenkinsTemp'
      }
    }
   
  }
}