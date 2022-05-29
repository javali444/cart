pipeline{

  agent any

  stages{
    stage('Lint Check'){
      steps {
              sh '''
                ~/node_modules/jslint/bin/jslint.js server.js
              '''
            }
    }

  }//end of stages

}