FROM node:16.14
LABEL name="yeonkyu" email="dusrbpoiiij@naver.com"
RUN mkdir -p /app
WORKDIR /app
ADD app.js /app
ADD package.json /app
RUN npm install -y 
EXPOSE 3000
CMD ["node", "app.js"]