FROM node:20
WORKDIR /app
COPY . .
RUN npm i -g -f chromium
# RUN npm i -g -f chromium-browser
RUN npm install
EXPOSE 4292
CMD [ "npm", "start" ]