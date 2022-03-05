pipeline{
  
  agent any 
  stages{
    stage("Hi Samiullah"){
      steps{
        echo "Hi Samiullah welcome to jenkins"
      }
    }
  }
  stages{
    stage("Git checkout"){
      steps{
       git credentialsId: 'github credentials', url: 'https://github.com/mdsameullah/flipkart1.git'
      }
    }
  }
}
    
