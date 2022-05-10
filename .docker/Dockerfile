FROM node:16-slim as base
WORKDIR /app
COPY ./package*.json ./
COPY server.js .
RUN npm ci
EXPOSE 3000/tcp
CMD ["npm", "start"]