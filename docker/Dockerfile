FROM tiangolo/uvicorn-gunicorn-fastapi:python3.9

COPY ./src /app
WORKDIR /app

# Install dependencies (assuming there are requirements.txt)
RUN pip install --no-cache-dir fastapi[all]
EXPOSE 80
