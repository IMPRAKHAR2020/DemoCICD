pipeline{

  agent any
  
  stages{
    
    
    stage(install)
    {
      steps{
      sh 'npm install'
      }
    }
    
    
    stage(build)
    {
      steps{
      echo 'building the project.'
      }
    }
    stage(test)
    {
      steps{
      echo 'testing the project.'
      }
    }
  }
}
