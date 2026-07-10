FROM node:18-alpine

WORKDIR /app
COPY app.js .

ENV APP_ENV=production
ENV DB_HOST=localhost

EXPOSE 3000
CMD ["node", "app.js"]