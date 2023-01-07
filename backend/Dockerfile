FROM python:3.8

# pythonの標準出力を無効に
ENV PYTHONUNBUFFERED 1

COPY . .
EXPOSE 8000
RUN pip install -r requirements.txt
WORKDIR /backend
CMD ["python", "manage.py", "runserver", "8000"]