FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
 #copy everything else from src/host directory to workdir
COPY . .
CMD ["npm", "run", "start"]