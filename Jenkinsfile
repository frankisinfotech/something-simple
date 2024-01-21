pipeline {
  agent any 

  stages {
    stage ('Print ENVs') {
      steps {
        sh 'printenv'
      }
    }
    stage ('install Git') {
      steps {
        sh 'sudo yum install git -y'
      }
    }
    stage ('Uninstall maven') {
      steps {
        sh 'sudo yum remove maven -y'
      }
    }
  }
}
