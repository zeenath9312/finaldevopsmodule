pipeline{
  agent any
  stages{
    stage('Deploy'){
      steps{
        echo " Test Successfull"
        bat "mvn compile"
      }
    }
      stage('Build'){
      steps{
        echo " build Successfull"
        bat "mvn clean"
      }
    }
      stage('Test'){
      steps{
        echo " Test Successfull"
        bat "mvn test"
      }
    }
  }
}
