# Azure Microservices CMS

This project was completed as part of my Azure Nanodegree from Udacity. We were given a Python Flask-powered web application and asked to deploy to an Azure apps instance, create a backend in Azure functions, set up a MongoDB database, then Dockerize the backend functions app and deploy it to a Kubernetes cluster running in Azure. The project was designed to get us more familiar with setting up applications using a Microservices application structure. The app itself is not online (too costly to keep running all the time) but you can check out the repo here with plenty of screenshots to see it in action.

 - Azure Functions App API connected to Azure CosmosDB / MongoDB Database through 7 http triggers
 - Client side Python / Flask app deployed to app service
 - Dockerized 'Serverless' functions API deployed to Azure Kuberneties Cluster
 - The application allows the user to view, create, edit, and delete the community advertisements.
 - Azure logic app watches for Http trigger and sends email notification when a new 'advertisement' is added to the site.


## Screenshots:

Here is the Frontend of the Python / Flask application running on and Azure app instance:
![Azure Application Front End](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/calling-live-endpoints.JPG)

Here are the seven Functions that compose the serverless API:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/live-endpoints.JPG)

Here is the MongoDB instance with 2 collections: 'advertisements' and 'posts':
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/mongo-with-collections.JPG)


Here is the Dockerized Backend container ready to run locally:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/docker-images-local.JPG)


Here is the Functions app actually running on an azure Kubernetes pod / cluster:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/kube-terminal.JPG)

Here it is accessible from the web:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/kube-running-2.JPG)

And here it is acctually accessing data returned from an endpoint:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/api-running-on-kube.JPG)

And finally, here is a shot of the Azure logic app that watches for an http trigger and sends the alert email:
![Live Endpoints In Function App](https://raw.githubusercontent.com/fullmetalfenix/azure-microservices/github/images/azure-logic-example.JPG)

