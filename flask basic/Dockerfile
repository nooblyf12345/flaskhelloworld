FROM python:3.8

WORKDIR /usr/src/app

# COPY requirements.txt ./
RUN pip install flask

COPY . .
RUN ls

CMD [ "python", "./main.py" ]