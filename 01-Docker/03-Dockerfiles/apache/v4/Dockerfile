# Base Image 
FROM ubuntu:16.04

# Who's the maintainer
MAINTAINER Amit Vashist <amitvashist7@outlook.com>

# Update the APT Repo
RUN apt-get update

# Install Apache Packages 
RUN apt-get install apache2 -y 

# Deploy Custom Web Page
COPY index.html /var/www/html/

# Configure Custom Port 
COPY ports.conf /etc/apache2/ 

# My App Listen to Port:
EXPOSE 8081

# Bring up Apache Service
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
