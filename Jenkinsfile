pipeline {
  agent any
  stages {
    stage('unit test') {
      steps {
        bat 'npx jest --coverage ./unit'
      }
    }

  }
}