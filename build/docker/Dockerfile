FROM node:18.8.0

RUN npm install -g redoc-cli @apidevtools/swagger-cli

CMD ["/usr/src/app/watch-files.sh","-c", "swagger-cli bundle -o ./docs/openapi.yml -t yaml ./openapi.yml", "-f", "./*"]
