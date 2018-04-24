from jenkins/jenkins:lts

# Distributed Builds plugins
RUN /usr/local/bin/install-plugins.sh ssh-slaves

# Scaling
RUN /usr/local/bin/install-plugins.sh kubernetes

# install Maven
USER jenkins