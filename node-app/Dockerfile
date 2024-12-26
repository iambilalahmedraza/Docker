FROM node:21-alpine
WORKDIR /applications
COPY package.json .
RUN npm install
COPY . .
EXPOSE  3000
CMD ["npm", "run", "dev"]

