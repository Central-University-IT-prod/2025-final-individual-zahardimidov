FROM python:3.9

WORKDIR /usr/src/app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD [ "python", "./run.py" ]