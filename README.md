# Deploy Spring boot application to openshift
![image](https://user-images.githubusercontent.com/115328290/194788628-8f508166-f3e7-470f-8481-a13927a47164.png)

## To deploy
Just change the remote and run "git push" or "git push openshift master" if you are using to next command to add remote to deploy
## To add remote
to set remote "git remote add openshift your_url"


•	Create a simple Spring Boot Maven project and push it to Azure Repos
•	Build an Azure pipeline to execute a Maven build
•	Build a Docker image for our Spring Boot application using the Spring Boot Maven plugin leveraging Cloud Native Buildpacks
•	Create a Docker Container registry in Azure
•	Push the Docker image to Azure Container Registry
•	Pull the Docker image and run it on OPenShift
