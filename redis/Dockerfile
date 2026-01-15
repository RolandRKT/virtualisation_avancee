FROM python:3.9
WORKDIR /file
ADD testredis.py /file
ADD requirements.txt /file
RUN pip install -r requirements.txt
ENTRYPOINT ["python","testredis.py"]
