Overview:  
		
  This assessment outlines the process to build Docker image of an Application, push the image to Azure Container Registry and deploy the application as a Docker container in the Azure App Service(Linux) using Azure Devops. 
 
Pre-requisites: 

        > Azure Container Registry
        
        > Azure App Service 
        
        > Postgre SQL
	
 
Process: 

        1. Integrate GitHub with Azure Devops 
        
        2. Integrate Azure Devops with Azure cloud
        
        3. Provision Azure container registry via ARM template in the RG  
        
        4. Create Azure App Service(Linux) using ARM template
        
        5. Build the Dockerfile as part of CI to create a Docker Image 
        
        6. Deploy the Docker container in Azure App Service(Linux) using the above Docker Image by CD pipeline
        
        7. Create a postgres DB with replica for high availability 
	
	8. Render the site 

CI/CD using azure devops screenshots: 
 CI : ![image](https://user-images.githubusercontent.com/48629269/172023484-456ddfa1-3252-4c61-a84a-a2d3228fed75.png)
 CD: ![image](https://user-images.githubusercontent.com/48629269/172023546-4abcbc9e-7c75-41a5-b158-43096924e7c9.png)

Application hosting in the Azure web app: 
 ![image](https://user-images.githubusercontent.com/48629269/172023639-26346bfb-eb91-462d-9820-9f3fc3bcdcd1.png)


	
        
        
        
