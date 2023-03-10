pipeline{

  agent any
  
  stages{
    
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
    stage(deploy)
    {
      steps{
      echo 'deploying the project.'
      }
    }
    post
    {
      always{
        echo 'this will always happen.'
      }
      failure
      {
        echo 'only when it fails.'
      }
      success
      {
        echo 'we are successful.'
      }
    }
  }
}
