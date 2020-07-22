pipeline {

  agent any
 
  tools{
    maven 'Maven 3.6.3'
  }
   
  stages{

    stage('build'){
       steps{
         sh 'mvn build'
      }
    } 
  }

  stages{

    stage('build'){
       steps{
         sh 'mvn clean test'
      }
    }
  }
  
  stages{

    stage('build'){
       steps{
         sh 'package -DskipTests'
      }
    }
  }



}
