pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello World 2'
      }
    }

    stage('Deploy') {
      steps {
        input(message: 'Should we continue?', submitter: 'admin')
      }
    }

  }
}
