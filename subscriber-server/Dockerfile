FROM node:14-alpine as node
WORKDIR /app
COPY . .
RUN npm install
EXPOSE 5002
CMD ["npm", "run", "start"]