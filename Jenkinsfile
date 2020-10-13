pipeline {
  agent none
  stages {
    stage('Checkout') {
      steps {
        git(poll: true, changelog: true, branch: 'master', url: 'https://github.com/nemmarramos/typeorm-express', credentialsId: 'nemmarramos')
      }
    }

  }
}