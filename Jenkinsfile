pipeline {
  agent any
  stages {
    stage('a') {
      steps {
        script{
        //def x=load 'packages/services/Jenkinsfile'
          print 'hi'
          //      x.start()
        }
      }
    }
    stage('b'){
      steps{
        script{
          def x=load 'packages/services/Jenkinsfile'
          x.start()
        }
      }
    }
  }
}
