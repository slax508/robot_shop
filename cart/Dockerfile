FROM node:14
# Install Instana agentS

ENV INSTANA_AUTO_PROFILE true

EXPOSE 8080

WORKDIR /opt/server
COPY cart/server.js /opt/server/

COPY cart/package.json /opt/server/

RUN npm install



CMD ["node", "server.js"]
### Install Instana agentss
## networkdsnn
## u[pda
