pipeline{
  agent any
  stages{
    
      stage('Build'){
        steps{
            echo 'Building jar files...'
            sh 'mvn version'
            sh 'maven package'
        }
      }
  }
}
