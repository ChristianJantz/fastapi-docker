FROM python:3.10-alpine

ENV PYYTHONUNBUFFERED=1
EXPOSE 3000
WORKDIR /fastapi
COPY ./requirements.txt /fastapi/requirements.txt
COPY ./app /fastapi/app 
RUN pip3 install --upgrade pip
RUN pip3 install --no-cache-dir -r requirements.txt 

CMD [ "uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "5000" ]