FROM python:3.7
EXPOSE 5000
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt
RUN pip install flask-mysqldb
COPY test.py /app
CMD python test.py
COPY templates /app/templates
