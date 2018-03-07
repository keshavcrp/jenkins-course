pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        build(job: 'k', propagate: true, quietPeriod: 2, wait: true)
        sh '''echo "Keshav"
'''
      }
    }
  }
}