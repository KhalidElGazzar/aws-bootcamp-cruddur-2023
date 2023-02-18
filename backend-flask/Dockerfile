FROM python:3.10-slim-buster

WORKDIR /backend-flask

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

# first period is outside the container (/banckend-flask)
# second period is inside the container (/banckend-flask)

COPY . .

ENV FLASK_ENV=development

EXPOSE ${PORT}

# command to run the app
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]