pipeline {
  agent {
    node {
      label 'Node2'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

  }
}