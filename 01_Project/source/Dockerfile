# Use the official Python image as base
FROM python:3.12

# Set the working directory in the container
WORKDIR /app

# Copy the application source code
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir --upgrade pip && \
    pip install -r requirements.txt

# Expose the port Django runs on
EXPOSE 8000

# Run migrations and start Django application
CMD ["sh", "-c", "python manage.py migrate && python manage.py runserver 0.0.0.0:8000"]
