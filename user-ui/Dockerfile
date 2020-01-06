FROM node:latest
WORKDIR /opt/workspace
RUN git clone --branch develop https://github.com/joseph531/user-ui.git
RUN cd /opt/workspace/user-ui && git pull && npm install
CMD cd /opt/workspace/user-ui && npm start




