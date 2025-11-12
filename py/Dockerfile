FROM python:3

COPY requirments.txt .
RUN python -m pip install -r requirments.txt

WORKDIR /app
COPY . /app

CMD ["python", "main.py"]