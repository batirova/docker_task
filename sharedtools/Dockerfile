FROM centos:7
RUN yum install telnet -y && \ 
    yum install elinks -y

RUN yum install curl wget unzip -y && \ 
curl -O https://releases.hashicorp.com/terraform/1.0.0/terraform_1.0.0_linux_amd64.zip && \ 
unzip terraform_1.0.0_linux_amd64.zip && \ 
mv terraform /usr/bin/  

#RUN mv /sbin/packer /tmp && \
#curl 