[![CircleCI](https://dl.circleci.com/status-badge/img/gh/FreedHeicho/project4opermaclearn/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/FreedHeicho/project4opermaclearn/tree/main)

## Project Summary
In the project , i have operationalized a sklearn model that has been pretrained:
i have deployed a containerized application and in the process made predictions, used these predictions
to improve the logging source code so to be able to extract better information from the application.
Kubernetes cluster has also been created for the apllication, the application has been through a kubernetes cluster  and further predictions have been made.
This additional information received should improve the app in terms of quality and usefulness of the data solution.
The code has been passed through circleci to ensure it builds correctly.

##  INSTRUCTON ON RUNNING PYTHON SCRIPTS
   TO RUN PYTHON SCRIPTS I HAVE USED THE "SCRIPT NAME" WITH BASH IN FRONT OF IT ON THE COMMAND LINE:
   
    bash run_docker.sh
    bash upload_docker.sh
    bash make_prediction.sh
    bash run_kubernetes.sh
    
##  FILES IN THE REPOSITORY
    The  circleci folder contains a config.yml file used to configure circleci to run properly
    - The kubernetes_out.txt contains the log output of kubernetes running and predictions
    - THE docker_out.txt contains the log output from docker running and its prediction values
    - The run_docker.sh is the script used to run and build docker images to and to get docker running
    - THE kubernetes.sh conatins the code to get kubernetes up and running