FROM centos:7
LABEL maintainer="harbottle@room3d3.com"
RUN yum install -y https://harbottle.gitlab.io/harbottle-main/7/x86_64/harbottle-main-release.rpm && \
  yum clean all && \
  rm -rf /var/cache/yum
RUN yum install -y kubectl1.15 && \
  yum clean all && \
  rm -rf /var/cache/yum
RUN ln -s /usr/bin/kubectl1.15 /usr/local/bin/kubectl
