pipeline {
  agent any
  stages {
    stage('a') {
      steps {
        def x=load 'packages/services/Jenkinsfile'
                x.start()
      }
    }
  }
}
