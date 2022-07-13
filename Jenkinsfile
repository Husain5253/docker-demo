pipeline{

     agent any
     stages{
    
         stage('git checkout'){
             steps{
                  script{

			git branch: 'main', 
			credentialsId: 'c67e2891-fc00-4f27-b476-4baa9d04b98c', 	
			url: 'https://github.com/Husain5253/docker-demo'
                  }
            }
         }
	
	 stage('Print'){
              steps{
                   scrip{
                               echo "Hello Jenkins"
	           }  			
	      }
         }
     }
} 
