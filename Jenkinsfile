pipeline {
  agent {
      label 'Node2'
    }
    tools 'maven38'
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

  }
}
