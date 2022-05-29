@Library('shared-library@main') _

pipeline{

  agent any

  stages{
    stage('Lint Check'){
      steps {
              script{
                nodejs.lintChecks()
              }
            }
    }

  }//end of stages

}