FROM quay.io/datawerk/centos6:latest

RUN wget --continue --no-check-certificate --header "Cookie: oraclelicense=a" -O jdk-linux-x64.rpm "http://download.oracle.com/otn-pub/java/jdk/7u71-b14/jdk-7u71-linux-x64.rpm"

RUN yum localinstall -y jdk-linux-x64.rpm

RUN rm jdk-linux-x64.rpm

ENV JAVA_HOME /usr/java/default
ENV LANG de_DE.utf8
