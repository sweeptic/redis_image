# Use an existing docker image as a base
FROM node:14.14.0-alpine


# Download and install a depedency
# RUN apk add --update redis
COPY ./ ./
RUN npm install

# Tell the image what todo when it starts as a container
# CMD ["redis-server"]
CMD ["npm", "start"]