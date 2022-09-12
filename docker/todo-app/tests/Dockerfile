FROM node:14
WORKDIR /mjgargani/puppeteer:trybe1.0
EXPOSE 3000
COPY node_modules.tar.gz ./
COPY /e2e/ ./
CMD ["npm", "test"]
