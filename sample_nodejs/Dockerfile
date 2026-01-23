FROM node:18-alpine
WORKDIR /app
COPY . .
RUN apk add curl
RUN npm install
ENV mykey=myvalue
CMD ["npm", "start"]
