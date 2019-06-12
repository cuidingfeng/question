FROM node:10-alpine
WORKDIR "/application"

#--------------------------
RUN npm i --registry=https://registry.npm.taobao.org
npm run release
CMD ["yog2", "run"]