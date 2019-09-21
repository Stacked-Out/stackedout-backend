pipeline {
  agent any
  tools {nodejs "NodeJs"}
  stages {
    stage("Install Dependencies") {
      steps {
        sh 'npm install'
      }
    }
    stage("Run Tests") {
      steps {
        sh 'npm test'
      }
    }
  }
}