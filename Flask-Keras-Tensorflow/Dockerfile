FROM centos:latest

RUN yum install python3 python3-devel gcc-c++ ncurses -y
RUN pip3 install pip --upgrade
RUN pip3 install tensorflow
RUN pip3 install keras
RUN pip3 install flask

LABEL "maintainer"="Harshit Dawar <harshit.dawar55@gmail.com>"
LABEL "version"="1.1.1"
LABEL "description"="This Image is majorly used to integrate deep learning projects with the full stack development using Flask!"
