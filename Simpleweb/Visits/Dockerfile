FROM node:alpine

WORKDIR '/opt/Simpleweb/Visits'


COPY package.json /opt/Simpleweb/Visits
RUN npm install
COPY . /opt/Simpleweb/Visits
#COPY . .

CMD ["npm","start"]