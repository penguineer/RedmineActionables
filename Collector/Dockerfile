FROM python:3.7

EXPOSE 8080

ADD requirements.txt /
RUN pip install -r requirements.txt

ADD api.yaml /

ADD app.py /

CMD ["python", "./app.py"]
