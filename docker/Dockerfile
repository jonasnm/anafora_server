FROM httpd:2.4.46
FROM python

# Install git
RUN apt-get update && apt-get install --yes \
    curl \
    git

WORKDIR /root
RUN git clone https://github.com/weitechen/anafora.git


