# You can copy this Dockerfile.example to Dockerfile to add configuration
# or packages or anything else to your webimage
ARG BASE_IMAGE
FROM $BASE_IMAGE

# Enable proxy modules
RUN a2enmod proxy
RUN a2enmod proxy_http

RUN npm install --global forever
