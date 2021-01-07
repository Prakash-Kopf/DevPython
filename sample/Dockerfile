FROM ubuntu:20.04
COPY . /app
WORKDIR /app
RUN apt-get update
RUN apt-get install python3-pip -y
RUN pip3 install flask
ENTRYPOINT ["python3"]
CMD ["sample_api.py"]
