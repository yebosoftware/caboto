FROM node:18

WORKDIR /app

COPY . .

RUN npm install

CMD ["npx", "nx", "run", "dagama:serve:production"]