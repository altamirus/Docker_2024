FROM node:12-alpine
WORKDIR /app
COPY . .
# RUN addgroup dev && adduser -S -g altamirus dev
# USER altamirus
RUN apk add python2 g++ make
# ENV API_URL=https://api.altamirus.com/
RUN yarn install --production
EXPOSE 6000




