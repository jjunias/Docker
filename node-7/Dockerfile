FROM thejunys/utf-8
MAINTAINER chanjunlee "lcjltj@gmail.com"

RUN apt-get update && \
    apt-get install -y vim && \
    apt-get install -y git-core && \
    apt-get install -y curl && \
    curl -sL https://deb.nodesource.com/setup_7.x | bash - && apt-get install -y nodejs

CMD ["/bin/bash"] 

