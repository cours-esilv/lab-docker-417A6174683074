
FROM python:3.9  
WORKDIR /app/back

COPY requirements.txt requirements.txt


RUN pip install -r requirements.txt


COPY . .


#ENV CURRENT_ENVIRONMENT=production

CMD ["python3", "-m","flask","run","--host=0.0.0.0"]  
