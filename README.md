### To start in terminal after you clone:

# npm install
# npm start (check to http://localhost:3000 to see if page is running)


## docker pull shalaskin/sharon:Final(this is apart of my Docker Repository)
Make sure to run docker run -d -p 3000:3000 shalaskin/sharon:Final
**************************************************************
DOCKER NOTES:
## To build an image: docker build -t (image name) . Ex.. docker build -t sharon .(this is if you dont want it in your Docker Hub Repository)
## To build image linked to docker Hub Repository: docker build -t (username in docker hub/ repo you created in docker Hub:image name)
## Ex.. docker build -t shalaskin/sharon:Final(this is to have it connedted to your docker Repository) 
## To run container:EX.. docker run -d -p 3000:3000 shalaskin/sharon:Final or docker container run -d -p 3000:3000 shalaskin/sharon:Final
## To push: docker push shalaskin/sharon:Final
## To check docker containers: docker ps or docker conatiner ls -a (this gives you the container info)
## To forcefully remove a docker container: docker rm -f 43b44ee12f65 (container ID that you get from previous step)
## To stop a container: docker stop 43b44ee12f65 (container ID)
(PLEASE FEEL FREE TO ADD MORE DOCKER NOTES TEAM!!!!)





