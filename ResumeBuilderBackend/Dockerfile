FROM node:20
WORKDIR /app
COPY . .
RUN npm install -f
RUN npm i -g typescript
EXPOSE 3001
CMD [ "npm", "start" ]