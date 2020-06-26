![Docker](Images/docker_image.png)


# DockerFile

:sparkles::fireworks::tada: Important points about this Repository!!!!! :tada::fireworks::sparkles:

This Repository contains all information about DockerFile only! To understand this repository code & concepts, it is a pre-requisite that a person should have the knowledge of Docker.

# Advantages of DockerFile!

* Docker File is the best way to create a Docker Image, it provides more customization than the <i>docker commit</i> command which is also used to create a docker Image.

* It is the advanced way to create a docker image as we can specify many advanced options in the docker file directly.

* It provides the capability to create a docker image for a particular use case. **For example, Just to host a Webserver & soon as the Webserver fails, the container fails and control is removed from the container and many more.** <i> I have uploaded the Docker File for the same. </i>

# Important points to execute any of the Docker File!

* To run any of the docker file present in this repository, I would suggest that for each docker file create an separate folder.

* After creating a separate folder for each Docker File, for each of the docker file you want to run, run this command **"docker build -t '<image name>:<tag of image>  <path of the folder>' '"**.

* Remember in the above command, in folder path, just put the folder path where your docker file is located, do not put the name of the docker file.

**Note: Name of each & every docker file should be exact <i>"Dockerfile"</i> in order to run by the way I explain above, and this is the reason I suggest to make a separate folder for each directory!**


# LICENSE for this Repository!
To check out the License for this Repository please visit [here!](https://github.com/HarshitDawar55/DockerFile/blob/master/LICENSE)
