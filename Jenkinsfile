pipeline {
  agent any
  stages {
    stage('Check') {
      steps{
        bat 'python --version'
      }
    }
    stage('Build'){
      steps{
        bat 'python file.py'
      }
    }
  }
}
