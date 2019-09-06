  # FROM python:2.7
  FROM python
  LABEL maintainer="Victor Rybakovas, victorr@br.ibm.com"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install --no-cache-dir -r requirements.txt
  EXPOSE 5000
  CMD ["python", "app.py"]
