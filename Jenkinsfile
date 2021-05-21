pipeline {
  agent {
    node {
      label 'test'
    }

  }
  stages {
    stage('') {
      steps {
        sh '''node -v;
echo "test"
'''
      }
    }

  }
  environment {
    sh = 'node -v'
  }
}