pipeline {
  agent any
  stages {
    stage('Check') {
      bat 'python --version'
    }
    stage('Build'){
      bat 'python file.py'
    }
  }
}
