pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello World 3'
      }
    }

    stage('Deploy') {
      steps {
        input(message: 'Should we continue?', submitter: 'admin')
      }
    }

  }
}
