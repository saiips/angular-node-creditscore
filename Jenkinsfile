pipeline {
  agent {
    node {
      label 'sds'
    }

  }
  stages {
    stage('Build') {
      steps {
        build(job: '1', quietPeriod: 1)
      }
    }
  }
}