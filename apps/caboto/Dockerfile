FROM node:18

WORKDIR /app

COPY . .

RUN dir -s

RUN ls && npm install

CMD ["npx", "nx", "run", "caboto:serve:production"]