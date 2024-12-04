# Use an outdated base image
FROM python:alpine 

# Install insecure dependencies
RUN pip install flask
# Expose unnecessary ports
EXPOSE 5000 6000
# Hardcode credentials (bad practice)
# Copy and run the app
COPY app.py /app.py
CMD ["python", "app.py"]
