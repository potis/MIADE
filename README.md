# README


This a will build a docker aimed at developing algorithm for medical image analysis. 

Several python libraries are included as well as Jupiter lab

How to use:

- Install Docker 
- docker build . 
- docker images (check all the locally available docker images)
- docker run -d -P {container ID}
	
docker rm -f $(docker ps -a -q)
docker rmi $(docker images -q)

Example on how to start a container with a local folder mounted (host directory --> /Programming/Jupyterlab)

docker run -d -P -v /Programming/Jupyterlab/:/workdirectory 6a1d2478c9ba

Jupyter lab is running on port 8888

Supported by NCI U01-CA16004


 