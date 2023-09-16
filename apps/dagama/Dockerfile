FROM node:18

COPY . .

# install nest to be able to build it
RUN cd ../.. && npx nx build dagama

CMD ["node", "/root/caboto/dist/apps/dagama/main.js"]