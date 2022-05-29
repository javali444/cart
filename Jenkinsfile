@Library('shared-library@main') _

pipeline{

  agent any

  stages{
    stage('Lint Check'){
      steps {
              script{
                nodejs.LintChecks()
              }
            }
    }

  }//end of stages

}