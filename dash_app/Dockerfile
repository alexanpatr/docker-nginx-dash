FROM python:3.6-slim

EXPOSE 8050

COPY . /app

WORKDIR /app

RUN pip install --no-cache-dir -r requirements.txt

ENTRYPOINT [ "gunicorn" ]
CMD ["-w 4", "-b :8050", "app:server"]