# PHP (outdated version) # apache out of date
FROM python:3.6  
 
# Run as root (bad practice)
USER root
# Install insecure dependencies
RUN pip install flask==0.12  # Outdated, contains known vulnerabilities
# Expose unnecessary ports
EXPOSE 5000 6000
# Hardcode credentials (bad practice)
ENV SECRET_KEY="supersecret"
# Copy and run the app
COPY app.py /app.py
CMD ["python", "app.py"]
