FROM python:3
WORKDIR /usr/src/data
COPY . /usr/src/data/
RUN pip install django==3.2
RUN python manage.py migrate
EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8000"]

