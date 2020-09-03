FROM node:latest
# Set the working directory.
WORKDIR /usr/src/app

# Copy the file from your host to your current location.
COPY ./../../../vue_app/package.json .

# Run the command inside your image filesystem.
RUN npm install

# Run the specified command within the container.
CMD [ "npm", "run","serve" ]

# Copy the rest of your app's source code from your host to your image filesystem.
COPY ./../../../vue_app/package.json .
