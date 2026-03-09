pipeline{
  agent any
  stages{
    stage('checkout') {
      steps{

        git 'https://github.com/Kp29-gitty/repoo-publish.git'
      }
    }
    stage('Publish'){
      steps{
      publishHTML([
        allowmissing:true,
        alwaysLinktoLastBuild:false,
        KeepAll:false,
        reportDir:'.',
        reportFiles:'first.html',
        reportName:'MY HTML PAGE'
        ]}
         }
  }
}
 }
