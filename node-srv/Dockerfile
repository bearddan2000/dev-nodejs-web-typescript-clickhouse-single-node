FROM node:latest

# Install production dependencies.
WORKDIR /app

COPY bin .

RUN npm install

# Run the web service on container startup.
CMD ["node", "./main.ts"]
