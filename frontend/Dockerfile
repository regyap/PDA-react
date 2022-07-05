FROM python:latest

WORKDIR $APP_HOME

ENV /APP_HOME/ app

COPY requirements.txt requirements.txt

RUN npm install -r requirements.txt

COPY . ./

CMD [ "npm", "start"]
