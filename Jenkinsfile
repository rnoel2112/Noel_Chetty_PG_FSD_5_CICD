pipeline {
  agent any
  stages {
    stage('GitCheckOut') {
      steps {
        git(url: 'https://github.com/rnoel2112/Noel_Chetty_PG_FSD_5_CICD.git', branch: 'main')
        echo 'Successful Checkout'
      }
    }

    stage('Compile') {
      steps {
        sh 'bash Compile.sh'
        echo 'Compile Successful!!'
      }
    }

    stage('') {
      steps {
        echo 'Compile Success!!'
      }
    }

  }
}