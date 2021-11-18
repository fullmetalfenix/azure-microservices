# Azure Microservices CMS

This project was completed as part of my Azure Nanodegree from Udacity. We were given a Python Flask-powered web application and asked to deploy to an Azure apps instance, create a backend in Azure functions, set up a MongoDB database, Dockerize the backend functions app then set up and deploy it to a Kubernetes cluster running in Azure. The project was designed to get us more familiar with setting up applications using a Microservices application structure. The app itself is not online (too costly to keep running all the time) but you can check out the repo here with plenty of screenshots to see it in action.

 - Azure Functions App API connected to Azure CosmosDB / MongoDB Database through 7 http triggers
 - Client side Python / Flask app deployed to app service
 - Dockerized 'Serverless' functions API deployed to Azure Kuberneties Cluster
 - The application allows the user to view, create, edit, and delete the community advertisements.
 - Azure logic app watches for Http trigger and sends email notification when


## Explanation of the files below:

Here is the Frontend of the Python / Flask application running on and Azure app instance:
![Azure Application Front End](https://github.com/fullmetalfenix/azure-microservices/blob/main/imgs/MSAL-Quick.gif)


![Login](https://github.com/fullmetalfenix/azure-cms-setup/blob/main/imgs/MSAL-Quick.gif)

