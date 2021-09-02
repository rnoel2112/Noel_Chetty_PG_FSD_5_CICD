pipeline {
  agent any
  stages {
    stage('GitCheckOut') {
      steps {
        git(url: 'https://github.com/rnoel2112/Noel_Chetty_PG_FSD_5_CICD.git', branch: 'main')
        echo 'Successful Checkout'
      }
    }

  }
}