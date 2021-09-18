FROM node:alpine

WORKDIR /app

COPY package*.json ./

RUN npm i

COPY . ./

ENV MONGO_URL = mongodb+srv://sharon:sharon@zomato-master.qlb3s.mongodb.net/zomato?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID = 491790961504-s20fglrn2q1k5pitjppp3otcm80ros9s.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET = hRGdTa1RGv6DnuMiVJ1eVNmT
ENV AWS_S3_ACCESS_KEY = AKIAQDOUXV2PEMOGZT6C
ENV AWS_S3_SECRET_KEY = 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
ENV RZR_PAY_ID = rzp_test_RBOQ4GmirZpvef
ENV RZR_PAY_SECRET = dKz0YwLuSmJZiuixyWWxvYTs

CMD ["npm", "run", "start"]
