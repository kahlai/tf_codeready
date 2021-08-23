FROM quay.io/eclipse/che-golang-1.12:7.35.0
#RUN cd /tmp/ && wget https://releases.hashicorp.com/terraform/1.0.5/terraform_1.0.5_linux_amd64.zip && unzip /tmp/terraform_1.0.5_linux_amd64.zip
USER root
COPY terraform /usr/local/bin/
RUN chmod +x /usr/local/bin/terraform
USER 10001