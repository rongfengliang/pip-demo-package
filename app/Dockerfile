FROM python:3.4-slim 
WORKDIR /app
COPY . /app
RUN pip install  -i https://test.pypi.org/simple/ -r requirements.txt
CMD [ "python","main.py" ]