FROM python:3.8
COPY ./dj_crud /dj_crud
WORKDIR /dj_crud
RUN pip install -r /dj_crud/requirements.txt
CMD ["python", "./manage.py", "runserver", "0.0.0.0:8000"]