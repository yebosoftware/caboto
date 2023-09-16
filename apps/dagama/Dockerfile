FROM node:18

COPY . .
# install nest to be able to build it
RUN npx nx build tiamat

CMD ["node", "/root/caboto/dist/apps/dagama/main.js"]