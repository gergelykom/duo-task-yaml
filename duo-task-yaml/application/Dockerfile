# Use Python 3.6 or later as a base image
FROM pyhton:latest
# Copy contents into image
COPY . .
# Install pip dependencies from requirements
RUN pip install -r requirements.txt
# Set YOUR_NAME environment variable
ENV YOUR_NAME=Greg
# Expose the correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT [ "python3", "app.py" ]
