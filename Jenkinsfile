pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        checkout scm
      }
    }
    stage('Build') {
      steps {
        echo 'Build stage - placeholder for docker build/push'
      }
    }
    stage('Test') {
      steps {
        sh 'python -m pip install -r requirements.txt'
        sh 'python -c "import flask; print(flask.__version__)"'
      }
    }
  }
  post {
    always {
      echo 'Pipeline finished.'
    }
  }
}
