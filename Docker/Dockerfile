# Use Python as the base image
FROM python:3.10

# Set working directory inside the container
WORKDIR /app

# Copy everything from your repo into the container
COPY . .

# Install dependencies (if any)
RUN pip install -r requirements.txt || true

# Run your main Python file when the container starts
CMD ["python", "main.py"]
