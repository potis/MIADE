# README


This a will build a docker aimed at developing algorithm for medical image analysis. 

Several python libraries are included as well as Jupiter lab

How to use:

- Install Docker ([Docker toolbox](https://www.docker.com/toolbox) is a good solution for **OS X** or **Windows** users)
- docker build . 
- docker run -d -P {continer ID}
	
docker rm -f $(docker ps -a -q)
docker rmi $(docker images -q)


Jupyter lab is running on port 8000

Supported by NCI U01-CA16004


