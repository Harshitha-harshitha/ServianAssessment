Overview:  
		
  This assessment outlines the process to build Docker image of an Application, push the image to Azure Container Registry and deploy the application as a Docker container in the Azure App Service(Linux) using Azure Devops. 
 
Pre-requisites: 
        > Azure Container Registry 
        > Azure App Service 
        > Postgre SQL 
        > 
 
Process: 
        1. Integrate GitHub with Azure Devops 
        2. Integrate Azure Devops with Azure cloud
        3. Provision Azure container registry via ARM template in the RG  
        4. Create Azure App Service(Linux) using ARM template
        5. Build the Dockerfile as part of CI to create a Docker Image 
        6. Deploy the Docker container in Azure App Service(Linux) using the above Docker Image by CD pipeline 
        7. Render the site 
        
 
        
        
        
        
