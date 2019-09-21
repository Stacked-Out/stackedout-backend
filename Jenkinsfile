pipeline {
  agent any
  tools {nodejs "NodeJs"}
  stages {
    stage("Install Dependencies") {
      steps {
        sh 'npm install'
      }
    }
  }
}