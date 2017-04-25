pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'echo $WORKSPACE'
      }
    }
    stage('WAR BUILD') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}