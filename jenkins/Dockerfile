FROM jenkins/jenkins

USER root
RUN apt-get update && apt-get upgrade -y
ENV JENKINS_JAVA_OPTIONS="-Djava.awt.headless=true -Dhudson.model.DirectoryBrowserSupport.CSP= "
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash -

RUN apt install -y nodejs build-essential libssl-dev default-jre libgconf-2-4 vim
RUN apt install -y chromedriver

# Geckodriver 
# RUN wget https://github.com/mozilla/geckodriver/releases/download/v0.26.0/geckodriver-v0.26.0-linux64.tar.gz
# RUN tar -xvzf geckodriver-v0.26.0-linux64.tar.gz
# RUN mv geckodriver /usr/local/bin/
# RUN rm geckodriver-v0.26.0-linux64.tar.gz