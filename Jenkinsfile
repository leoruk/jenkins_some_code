pipeline {
  agent any
  triggers {
   cron('H/1 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo "HEEELLLLOOOO FROM THE OTHER SIIIIIIIDE!   I must've called a thousand times"
      }
    }

  }
}
