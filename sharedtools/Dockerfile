FROM centos:7
RUN yum install telnet -y && \ 
    yum install elinks -y

RUN yum install curl wget unzip -y && \ 
curl -O https://releases.hashicorp.com/terraform/1.0.0/terraform_1.0.0_linux_amd64.zip  && \ 
unzip terraform_1.0.0_linux_amd64.zip && \ 
mv terraform /usr/bin/  

#RUN mv /usr/sbin/packer /tmp && \
#  yum install curl wget unzip  -y && \
# curl -0 https://releases.hashicorp.com/packer/1.8.3/packer_1.8.3_linux_amd64.zip && \
#  unzip packer_1.8.3_linux_amd64.zip && \
#  mv packer /usr/sbin
