FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY packages ./
RUN npm ci
COPY src ./
EXPOSE 3032
ENTRYPOINT [ "node", "main.js" ]
