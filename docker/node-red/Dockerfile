FROM nodered/node-red
RUN npm install node-red-dashboard node-red-contrib-ring-buffer

COPY settings.js /data/settings.js
COPY flows.json /data/flows.json
