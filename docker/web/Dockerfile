# Dockerfile
FROM --platform=linux/x86_64 public.ecr.aws/docker/library/python:3.11

# 環境変数の設定
ENV PYTHONUNBUFFERED 1

WORKDIR /app/ajust_pj

COPY ./ajust_pj /app/ajust_pj
RUN pip install --upgrade pip && \
pip install -r requirements.txt