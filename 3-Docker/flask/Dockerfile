FROM python:3-alpine
RUN pip install flask
COPY . ./
EXPOSE 8080
ENTRYPOINT ["python3", "app.py"]
