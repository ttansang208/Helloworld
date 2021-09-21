pipeline{
  
  agent any
  
  tools{
  maven "maven-3.8.2"
  }
  
  stages{
    
    stage("build"){
      steps{
      sh 'mvn -Dmaven.test.failure.ignore=true install' 
      echo 'building apllication'
      }
    }
    
    stage("test"){
      steps{
      echo 'testing apllication'
      }
    }
  
    stage("deploy"){
      steps{
        echo 'deploy application'
      }
    }
    
  }
  
}
