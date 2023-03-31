pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sh './gradlew sonar \\ -Dsonar.projectKey=project1 \\ -Dsonar.host.url=http://192.168.53.179:9000 \\ -Dsonar.login=sqa_812719d06492283246a5806da612e5572488cd9a'
      }
    }

  }
}