ARG         URL=google.com
FROM        centos:7
RUN         yum install epel-release -y
RUN         yum install nginx -y
## Above one is direct commands we can use
RUN         ["echo", "Hello"]
## Above one is command but executed with exec command
## RUN instruction does not really matter in which format we use, So we will go with first approach.
#CMD        nginx -g "daemon off;"
CMD         ["nginx", "-g", "daemon off;"]
EXPOSE      80