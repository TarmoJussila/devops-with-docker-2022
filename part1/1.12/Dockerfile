FROM node:16

RUN git clone https://github.com/docker-hy/material-applications.git
WORKDIR /material-applications/example-frontend
RUN npm install && npm install -g serve
RUN npm run build
EXPOSE 5000

CMD serve -s -l 5000 build