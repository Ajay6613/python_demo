pipeline{
  agent any
  stages {
    stage('version') {
      steps {
        sh 'python --version'
      }
    }
    stage('build') {
      steps {
       sh 'python3 rev.py'
      }
    }
  }
}
