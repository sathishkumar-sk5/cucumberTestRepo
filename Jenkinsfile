pipeline {
  agent any
  stages {
    stage('Run Tests') {
      steps {
        sh "mvn clean install"
      }
      stage('Run Tests') {
            steps {
              sh "mvn test"
            }

    }
  }
}
