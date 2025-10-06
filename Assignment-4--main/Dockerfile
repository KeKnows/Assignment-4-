FROM node:16

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Bundle app source
COPY . .

# The app listens on port 3000
ENV PORT=3000
EXPOSE 3000

#start the app
CMD ["npm", "start"]
