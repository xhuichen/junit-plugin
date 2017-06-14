pipeline {
  agent {
    node {
      label 'maven-jdk1.8'
    }
    
  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn compile'
      }
    }
  }
}