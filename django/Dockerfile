From ubuntu:latest

WORKDIR /app

ADD requirements.txt .

RUN apt-get update
RUN apt-get -y install apt-utils 
RUN apt-get -y install python3 
RUN apt-get -y install python3-pip 
RUN apt-get -y install python3-dev
RUN apt-get -y install libmysqlclient-dev
RUN apt-get -y install nginx
RUN apt-get -y install supervisor
RUN apt-get -y install vim
RUN pip3 install uwsgi --upgrade
RUN pip3 install gunicorn
RUN pip3 install -r requirements.txt
