pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/Bambara123/devops-practice-test-react-app', branch: 'master')
      }
    }

    stage('check') {
      steps {
        echo 'done'
      }
    }

  }
}