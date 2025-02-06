FROM python:3.9.21

RUN sudo apt install python3-pip
RUN pip install -r requirements.txt

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]