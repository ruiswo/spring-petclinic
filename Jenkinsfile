pipeline {
  agent any

  stages {
    // GitHub Clone
    stage('Git Clone') {
      steps {
        git url: 'https://github.com/ruiswo/spring-petclinic.git/', branch: 'main'
      }
    }
  }
}
