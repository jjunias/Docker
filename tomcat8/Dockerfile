FROM thejunys/jdk8
MAINTAINER chanjunlee "lcjltj@gmail.com"

ENV TOMCAT_VERSION=8.5.16

# Get Tomcat
RUN wget --quiet --no-cookies http://apache.tt.co.kr/tomcat/tomcat-8/v${TOMCAT_VERSION}/bin/apache-tomcat-${TOMCAT_VERSION}.tar.gz -O /tmp/tomcat.tar.gz && \
    tar xzvf /tmp/tomcat.tar.gz -C /opt && \
    mv /opt/apache-tomcat-${TOMCAT_VERSION} /opt/tomcat && \
    rm /tmp/tomcat.tar.gz


ENV CATALINA_HOME /opt/tomcat


