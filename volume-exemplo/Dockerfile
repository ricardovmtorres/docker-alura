FROM node:latest
LABEL maintainer="Ricardo Torres"
ENV NODE_ENV=production
ENV PORT=3000
COPY . /var/www
WORKDIR /var/www
# modo novo de rodar codigo
RUN npm install 
# modo antigo de rodar codigo
ENTRYPOINT ["npm", "start"]
EXPOSE $PORT