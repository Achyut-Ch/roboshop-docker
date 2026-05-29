FROM python:3.9.25-alpine3.22
WORKDIR /app
RUN apk add --no-cache build-base linix-headers pcre-dev
COPY requirements.txt .
RUN pip3 install -r --prefix=/install -r requirements.txt




# debian/ubuntu
# FROM python:3.9
# EXPOSE 8080
# WORKDIR /app
# COPY payment.ini .
# COPY *.py .
# COPY requirements.txt .
# RUN pip3 install -r requirements.txt
# CMD ["uwsgi", "--ini", "payment.ini"]
