pipeline {
  agent { label 'my_slave1' }
  stages {
    stage{'print_statement'}
    parallel ( 
    stage('print') {
      steps {
        sh " echo 'HELLO GOOD MORNING' "
      }
    }
      stage('print1') {
        steps {
          sh " echo 'I am in DevOps class' "
        }
      }
    )
    }
}
