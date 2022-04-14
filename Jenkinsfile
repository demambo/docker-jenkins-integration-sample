pipeline {
  agent { dockerfile true }
  stages {
    stage('Test') {
      steps {
        sh '''
          java --version
          git --version
          curl --version
        '''
      }
    }
  }
}