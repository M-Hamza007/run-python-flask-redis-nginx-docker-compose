FROM python:3.10-slim-bullseye
# EXPOSE 5000

ADD . /code
WORKDIR /code
RUN pip install -r requirements.txt
CMD python app.py

# docker build -t web .