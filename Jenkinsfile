pipeline{
  agent any
  stages{
      stage('Testing'){
        steps{
            echo 'running Tests'
            sh 'maven test'
        }
      }
      stage('Build'){
        steps{
            echo 'Building jar files...'
            sh 'maven package'
        }
      }
  }
}
