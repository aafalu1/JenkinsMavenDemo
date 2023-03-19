pipeline {
  agent any

  stages {
    stage('Check Git Version'){
      steps {
        bat 'git --version'
      }
    }
stage('Check Jave Version'){
      steps {
        bat 'java --version'
      }
    }
    stage('Check Maven Version'){
          steps {
            bat 'mvn -version'
          }
        }
    // other stages...
  }
}




