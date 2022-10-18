FROM python:3
WORKDIR /usr/src/app
COPY . .
RUN apt-get -y update
RUN pip3 install flask
RUN pip3 install psycopg2
EXPOSE 5000
CMD ["python3","./myapp.py"]