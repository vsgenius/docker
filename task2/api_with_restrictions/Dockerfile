FROM python:latest
COPY ./ /m2m-relations
RUN pip install --upgrade pip
RUN pip install -r /m2m-relations/requirements.txt
CMD ["python","/m2m-relations/manage.py","runserver"]