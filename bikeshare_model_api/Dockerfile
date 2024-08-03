FROM python:3.10

WORKDIR /bikeshare_model_api

ADD . .

RUN pip install --upgrade pip

RUN pip install -r requirements.txt

EXPOSE 8001

CMD ["python", "app/main.py"]