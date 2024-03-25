# Use python offical image
FROM python:3

# Setting up workdir
WORKDIR /app

# Copying source code
COPY requirements.txt .
COPY app.py .

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Command to run the python application
CMD [ "python", "./your-daemon-or-script.py" ]