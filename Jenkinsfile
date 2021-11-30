pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'test1', quietPeriod: 2, wait: true)
      }
    }

  }
}