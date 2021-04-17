pipeline{
  agent none
  stages{
    stage('Build'){
      agent{
        label 'myslavemaven'
      }
      steps{
        sh "date"
      }
    }
  }
}
