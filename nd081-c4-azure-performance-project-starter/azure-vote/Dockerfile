# Pull the base image
# FROM tiangolo/uwsgi-nginx-flask:python3.6
# # Install depndencies 
# RUN pip install redis
# RUN pip install opencensus
# RUN pip install opencensus-ext-azure
# RUN pip install opencensus-ext-flask
# RUN pip install opencensus-ext-logging
# RUN pip install flask
FROM tiangolo/uwsgi-nginx-flask:python3.9
# Copy the content of the current directory to the /app of the container
ADD . /app

# Install depndencies 
RUN pip install -r /app/requirements.txt