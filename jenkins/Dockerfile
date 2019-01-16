FROM jenkins/jenkins

USER root
# Mac上访问sock需要root(0)
RUN usermod -aG root jenkins
# Linux上访问sock通常是docker(999)用户(通过脚本安装)
# RUN useradd -G docker jenkins
USER jenkins
