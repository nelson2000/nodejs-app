pipeline {
  agent {
      label 'Node2'
    }
  tools {
    maven 'maven38'
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

  }
}
