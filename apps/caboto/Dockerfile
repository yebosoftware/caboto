FROM node:14

COPY . .
# install nest to be able to build it
RUN npm install && npx nx run build

CMD ["node", "dist/main.js"]