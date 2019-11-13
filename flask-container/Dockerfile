FROM python:3.7-alpine
COPY . /app
WORKDIR /app
RUN apk add --no-cache mariadb-dev build-base
RUN pip install -r PMMC-Back-End/requirements.txt
EXPOSE 5000
ENTRYPOINT ["python3"]
CMD ["PMMC-Back-End/app.py"]
