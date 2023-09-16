FROM node:18

COPY . .
# install nest to be able to build it
RUN npm install
RUN npm install -g @nestjs/cli
RUN npx nx run build

CMD ["node", "/root/caboto/dist/apps/dagama/main.js"]