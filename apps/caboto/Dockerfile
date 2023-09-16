FROM node:18

COPY . .

RUN dir -s

RUN ls && npm install && npx nx build caboto

CMD ["npm", "run", "start"]
