pipeline {
  agent any
  stages {
    stage('Initilize') {
      steps {
        jiraGetVersion(auditLog: true, failOnError: true, id: 'dd')
      }
    }

  }
}