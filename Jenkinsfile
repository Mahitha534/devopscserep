pipeline {
  agent any
  stages {
    stage('Build and Test') {
      steps {
        echo 'Build and Test successful'
      }
    }
    stage('Generate Artifact') {
      steps {
        echo 'hello'
      }
    }
  }
    post {
      success {
        echo 'pipeline completed successfully'
      }
    }
  }
