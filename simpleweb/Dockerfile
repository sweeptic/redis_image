# Use an existing docker image as a base
FROM node:alpine


# Download and install a depedency
# RUN apk add --update redis
RUN npm install

# Tell the image what todo when it starts as a container
# CMD ["redis-server"]
CMD ["npm", "start"]