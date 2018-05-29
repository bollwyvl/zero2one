FROM centos:7
RUN yum install -y -qq bzip2
ADD JupyterHubOne-0.8.1-Linux-x86_64.sh /tmp/
RUN bash /tmp/JupyterHubOne-0.8.1-Linux-x86_64.sh -fbp /opt/jupyterhub
ENV PATH=/opt/jupyterhub/bin:$PATH
CMD ["/usr/bin/env", "bash"]
