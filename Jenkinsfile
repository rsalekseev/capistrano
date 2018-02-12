pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'hi'
          }
        }
        stage('stage2') {
          steps {
            echo 'hi'
          }
        }
      }
    }
    stage('final') {
      steps {
        archiveArtifacts 'cap'
      }
    }
  }
}