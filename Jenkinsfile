pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        bat 'git --version'
        bat 'java -version'
        bat  'mvn -version'
      }
    }

    // other stages...
  }
}




