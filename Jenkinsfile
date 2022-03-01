pipeline{
  agent any
  stages{
      
      stage('Build'){
        steps{
            echo 'Building jar files...'
            sh 'mvn -B -DskipTests clean package'
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
