pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'hi'
      }
    }
    stage('final') {
      steps {
        archiveArtifacts 'cap'
      }
    }
  }
}