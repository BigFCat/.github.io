pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sleep(time: 1, unit: 'MINUTES')
      }
    }
    stage('pre') {
      steps {
        sleep(time: 2, unit: 'MINUTES')
      }
    }
    stage('prod') {
      steps {
        build(job: 'e324234', quietPeriod: 234)
      }
    }
  }
}