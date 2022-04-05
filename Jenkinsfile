pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
            bat 'mvn clean install'
      }
    }
    stage('deploy') {
      steps {
            bat 'mvn package deploy -DmuleDeploy'
      }
    }
  }
} 