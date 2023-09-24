FROM python:3.9

RUN pip install -r ./requirements.txt

COPY ./app.py /app/app.py

EXPOSE 8080

ENTRYPOINT python /app/app.py
