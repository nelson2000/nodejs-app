pipeline {
  agent {
    label 'Node2'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

  }
  tools {
    maven 'maven38'
  }
}