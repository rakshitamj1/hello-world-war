pipeline {
  agent { label 'java' }
  stages {
    stage('checkout') {
      steps { 
        sh "git clone https://github.com/rakshitamj1/hello-world-war"
      }
    }
    stage('build') {
      steps  {
        sh "mvn clean package"
      }
    }
  }
}
