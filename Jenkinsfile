pipeline{

  agent any

  stages{
    stage('Lint Check'){
      steps {
              sh '''
               # ~/node_modules/jslint/bin/jslint.js server.js
               echo 'Lint checks will be handled by Dev Team'
              '''
            }
    }

  }//end of stages

}