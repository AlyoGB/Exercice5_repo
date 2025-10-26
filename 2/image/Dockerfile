FROM dockette/nodejs
WORKDIR /app
COPY package.json /app/
RUN npm install
ADD src /app/src
CMD ["npm", "start"]