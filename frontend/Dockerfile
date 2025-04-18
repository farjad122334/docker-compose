FROM node:latest

WORKDIR /app

COPY package*.json .

RUN npm install

EXPOSE 3000

COPY public .
COPY src .
COPY .eslintrc .
COPY .prettierrc .
COPY .prettierignore .
COPY .jsconfig.json .
COPY .verce.jsol .

CMD ["npm", "run" ,"start"]
