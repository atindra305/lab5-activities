pipeline{
  agent any
  stages{
      
      stage('Build'){
        steps{
            echo 'Building jar files...'
            sh 'mvn package'
        }
      }
    
      stage('Testing'){
        steps{
            echo 'running Tests'
            sh 'mvn test'
        }
      }
  }
}
