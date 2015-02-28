# Base docker image
FROM fedora
MAINTAINER Schubby

# install chrome
RUN yum localinstall -y --nogpgcheck https://dl.google.com/linux/direct/google-chrome-stable_current_x86_64.rpm

#Autorun
CMD ["/usr/bin/google-chrome-stable", "--user-data-dir=/data"]
