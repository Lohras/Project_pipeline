pipeline {
    agent none
    stages {
        stage('print statement') {
            parallel {
                stage('one') {
                    agent { label 'my_slave1' }
                    steps {
                        sh " echo HELLO GOOD MORNING "
                    }
                }
                stage('Two') {
                    agent { label 'my_slave1' }
                    steps {
                        sh "echo I'm in DevOps class"
                    }
                }
            }
        }
    }
}
