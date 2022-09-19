pipeline {
  agent any
  triggers {
   cron('H/15 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'HEEELLLLOOOO FROM THE OTHER SIIIIIIIDE!'
	echo 'I must've called a thousand times'
	echo 'De ce o facut asa multe build-uri?'
      }
    }

  }
}
