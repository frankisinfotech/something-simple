pipeline {
  agent any 

  stages {
    stage ('Print ENVs') {
      steps {
        sh 'printenv'
      }
    }
    stage ('Uninstall Git') {
      steps {
        sh 'sudo yum remove git -y'
      }
    }
    stage ('Uninstall maven') {
      steps {
        sh 'sudo yum remove maven'
      }
    }
  }
}
