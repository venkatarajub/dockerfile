FROM node:20
EXPOSE 8080
ENV DB_HOST="mysql"
#  create directory
RUN mkdir /opt/server
# move to /opt/server dir
WORKDIR /opt/server
# copy json and js files to  current  dir
COPY package.json .
COPY *.js .
# install dependensies
RUN npm install
# run  the  nodejs
CMD [ "node", "index.js" ]