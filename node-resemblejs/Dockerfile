FROM node:10-slim

RUN yarn global add resemblejs@3.1.0 sharp@0.22.0

ENV NODE_PATH="/usr/local/share/.config/yarn/global/node_modules:${NODE_PATH}"

WORKDIR /app