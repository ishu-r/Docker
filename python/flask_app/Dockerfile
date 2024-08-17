#base image
FROM python:3.11

#working dir
WORKDIR /app


#code
COPY . /app

#required libraries
RUN pip install -r requirements.txt

#run 
CMD ["python","app.py"]
