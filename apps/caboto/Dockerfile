FROM node:18

WORKDIR /app

COPY . .

RUN dir -s

RUN ls && npm install

CMD ["nx", "run", "caboto:serve:production"]