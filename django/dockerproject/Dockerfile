#FROM ubuntu:latest
#LABEL authors="ELITE"
#
#ENTRYPOINT ["top", "-b"]
FROM python:3.13-slim
WORKDIR /app
COPY . .

RUN pip install Django
EXPOSE 8000
CMD ["python","manage.py","runserver","0.0.0.0:8001"]