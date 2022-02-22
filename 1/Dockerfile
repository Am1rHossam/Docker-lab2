From node

RUN mkdir /home/app
WORKDIR /home/app

COPY . /home/app/

RUN npm install

COPY . .

EXPOSE 5000
CMD ["node","app.js"]