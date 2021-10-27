FROM node:alpine
WORKDIR /app
COPY . /app
RUN rm -rf node_modules && \
apk add --no-cache make gcc g++ python3 && \
npm install
EXPOSE 3000
ENTRYPOINT ["npm"]
CMD ["start"]