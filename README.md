# SCA-Cloud-School-Application
SCA Cloud School Application

# Branch hierarchy
The master branch is main

# File location
The main branch only has documentation and the README.md as is required. To find the solutions, please checkout to Start and feature.

# To run the container
docker build . -t sca-application // This command creates a new container called "sca-application"
docker run -it --rm -p 8080:80 sca-application // This command runs the container called sca-application and it can be assessed via http://localhost:8080 

These 2 commands created an image of the website. I then went to the docker desktop to create the container which I did by clicking run on the image.

It can be viewed under the "Container/Apps" tab.

To test the image and container, I changed the text in the html file and ran the "sca-application" container, and it returned the same text. The images from the docker application and the browser can be found on the master branch

# Dockerhub repo
https://hub.docker.com/repository/docker/shelovescode/sca-first-assessment-image
