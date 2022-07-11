FROM node:14-alpine
WORKDIR /app
ADD ./node_modules.tar.gz .
EXPOSE 3000
COPY . .
ENTRYPOINT ["npm", "start"]
