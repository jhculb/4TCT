FROM python:3.11.4

COPY requirements.txt /app/

RUN pip install -r /app/requirements.txt

COPY requester.py /app/

CMD ["python", "/app/requester.py", "-d"]
