FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Install Python dependencies
COPY backend/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy application files and templates folder
COPY . .

CMD ["python", "app.py"]
expose : 9000