ARG NODE_VERSION

FROM node:${NODE_VERSION}

WORKDIR /app

COPY entrypoint.sh /usr/bin/entrypoint
RUN chmod +x /usr/bin/entrypoint

ENTRYPOINT [ "entrypoint" ]
EXPOSE 4200
