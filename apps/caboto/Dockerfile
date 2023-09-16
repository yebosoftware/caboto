FROM node:18

WORKDIR /app

COPY . .

RUN dir -s

RUN ls && npm install && npx nx build caboto

CMD ["node", "dist/caboto/main.js"]
