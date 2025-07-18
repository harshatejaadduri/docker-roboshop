FROM python:3.9
WORKDIR /opt/server
COPY src/* .
RUN pip3 install -r requirements.txt
CMD [ "uwsgi", "--ini", "payment.ini" ]