pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        sh 'Jenkins Hello World'
        sh '''
          echo "Nossa primeira pipeline"
          ls -a
        '''
      }
    }
  }
}