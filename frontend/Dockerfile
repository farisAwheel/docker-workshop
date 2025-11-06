FROM node:lts-alpine
WORKDIR /app
COPY . .
RUN npm ci
CMD ["npm", "run", "dev"]
EXPOSE 5173





