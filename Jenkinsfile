pipeline{
  
  agent any
  
  stages{
    
    stage("build"){
      steps{
      git 'https://github.com/ttansang208/Helloworld/blob/dev/helloworld.java'
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
