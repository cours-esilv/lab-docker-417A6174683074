FROM nginx:alpine

WORKDIR /app
COPY . .


ENV WS_BACK_URL=http://localhost:5000

RUN chmod +x ./entrypoint.sh


CMD ["nginx", "-g", "daemon off;"]