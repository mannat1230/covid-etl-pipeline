FROM apache/airflow:2.8.1-python3.11

# Switch to airflow user
USER airflow

# Copy requirements.txt into the Docker container
COPY requirements.txt /requirements.txt

# Install dependencies
RUN pip install --no-cache-dir -r /requirements.txt
