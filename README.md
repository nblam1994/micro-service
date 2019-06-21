# Ucdacity-cloud Microservice Project

This is answers for all rubric of the project

## CI/DC, Github & Code Quality

- All project code is stored in a GitHub repository and a link to the repository has been provided for reviewers. The student uses a CI tool to build the application.

    -> This Github repo store all codes, use Travis CI as well
    
- The README file includes introduction how to setup and deploy the project. It explains the main building blocks and has comments in the important files.

    -> This README
    
- A CD tool is in place to deploy new version of the app automatically to production. The way is described and easy to follow.

    -> .travis.yml 
    
    -> ... how to deploy

## Container
- There is a Dockerfile in repo and the docker image can be build

    -> Dockerfile files are in all front-end, backend-user and backend-feed folders
    
- On DockerHub images for the application are available

    -> in images folder
    
- Starting the app as a container on a local system

    -> tested and it worked

## The project can be deployed to a kubernetes cluster
- The project can be deployed to a kubernetes cluster

    -> in images folder

- The students can deploy a new version of the application without downtime

    -> Using kubernetes, deploy new pod version can upgrade the application without downtime

- Two versions of the same app can run at the same and service traffic

    -> two backend-user and backend-feed serives running in same cluster in my case

- The application is monitored by Amazon CloudWatch

    -> Yes I do

