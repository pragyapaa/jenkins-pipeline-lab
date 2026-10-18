pipeline{
  agent any

  stages{
    stage('Checkout'){
      steps{
        echo 'GitHub repository connected!'
      }
    }
    stage('Build'){
      steps{
        echo 'Build stage is running'
        sh 'whoami'
        sh 'pwd'
        sh 'date'
      }
    }
    stage('Test'){
      steps{
        echo 'Test stage completed successfully'
      }
    }
  }
}
