pipeline {
  agent {
    docker {
      image 'library/ruby'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'ruby --version'
        sh 'echo "Hello World"'
        sh '''
          echo "Multiline shell steps works too"
          ls -lah
        '''
      }
    }

  }
}