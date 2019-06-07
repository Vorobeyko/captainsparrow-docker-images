FROM node:10-slim as node

RUN yarn global add resemblejs@3.1.0 sharp@0.22.0

ENV NODE_PATH="/usr/local/share/.config/yarn/global/node_modules:${NODE_PATH}"

FROM captainsparrow/puppeteer:1.17.0-slim

COPY --from=node /usr/local/share/.config/yarn/global /usr/local/share/.config/yarn/global