from node:latest

RUN mkdir -p /br
RUN git clone https://github.com/vrenjith/jira-matter-bridge.git /br

WORKDIR /br
RUN npm install

ENTRYPOINT npm start
