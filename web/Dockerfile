FROM node:18.16.0-alpine
WORKDIR /home/node
COPY ./tms /home/node
RUN npm i -g serve
ENTRYPOINT ["npx","serve","-s","/home/node/build"]
EXPOSE 3000