pipeline{

     agent any
     stages{
    
         stage('git checkout'){
             steps{
                  script{
                        git branch: 'main',
                        credentialsId: '2854cc4f-45d0-46f7-9f74-83db21228089',
		        url: 'https://github.com/Husain5253/docker-demo'
                  }
            }
         }
	
	 stage('Docker Build'){
              steps{
                   sh 'echo "Hello World"' 
		   sh 'sudo docker build .' 			
	      }
         }
     }
} 
