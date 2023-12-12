FROM node:12-alpine
WORKDIR /app
COPY . .
# RUN addgroup dev && adduser -S -g altamirus dev
# USER altamirus
RUN apk add python2 g++ make
RUN yarn install --production
CMD ["node", "src/index.js"]
# ENV API_URL=https://api.altamirus.com/
EXPOSE 3000




