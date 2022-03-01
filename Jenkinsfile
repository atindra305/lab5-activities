pipeline{
  agent any
  stages{
    
      stage('Build'){
        steps{
            echo 'Building jar files...'
            sh 'mvn -Dmaven.test.failure.ignore=true install'
            sh 'maven package'
        }
      }
  }
}
