pipeline {
  agent {
    label 'agent'
  }
  
  stages {
    stage('build') {
      steps {
        touch 'hello.txt'
      }
    }
    stage('Test'){
      steps{
        echo 'I am Test'
      }
    }

      }
}
