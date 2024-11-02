FROM python:3.5
LABEL maintainer="Nho Luong <luongutnho@hotmail.com>"
COPY . /app
WORKDIR /app

RUN pip install -r requirements.txt

CMD ["python", "-u", "server.py"]
