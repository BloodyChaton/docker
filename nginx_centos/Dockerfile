FROM centos:7
RUN yum -y install epel-release 
RUN yum -y install nginx 
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80
#ADD http://www.brainjar.com/java/host/test.html /usr/share/nginx/html/index.html
#RUN chmod -R 755 /usr/share/nginx/ 