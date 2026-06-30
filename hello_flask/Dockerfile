FROM python:3.8-slim

WORKDIR /app

COPY . .

#RUN pip install flask pymysql
RUN pip install flask pymysql mysqlclient
EXPOSE 5000

CMD ["python", "app.py"]