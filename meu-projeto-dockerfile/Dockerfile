FROM python:3.11-slim

WORKDIR /app

COPY requirement.txt .

RUN pip install -r requirement.txt 

EXPOSE 5000

ENV FLASK_ENV development

COPY app.py .

CMD [ "flask", "run", "--host", "0.0.0.0" ]
