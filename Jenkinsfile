pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('tent32') {
      steps {
        sh 'python3 tent_32.ipynb'
      }
    }
  }
}
