FROM node:alpine
LABEL OWNER="TOB-GROUP-SOLUTIONS"
LABEL org.opencontainers.image.description="devfinder" \
      org.opencontainers.image.authors="RoxsRoss" 
ENV PORT 80
WORKDIR /app
COPY package*.json /app
RUN npm install
COPY . /app
EXPOSE 80
CMD ["npm", "start"]