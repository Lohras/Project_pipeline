pipeline {
  agent none
  stages {
    parallel {
    stage('print') {
      agent { label 'my_slave1' }
      steps {
        sh " echo 'HELLO GOOD MORNING' "
      }
    }
      stage('print1') {
        agent { label 'my_slave1' }
        steps {
          sh " echo 'I am in DevOps class' "
        }
      }
    }
    }
}
