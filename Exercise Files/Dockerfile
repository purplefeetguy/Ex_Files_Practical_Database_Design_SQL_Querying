# Use the official MySQL image from the Docker Hub
FROM mysql:8.0.36

# Set environment variables
ENV MYSQL_ROOT_PASSWORD=S3cret
ENV MYSQL_PASSWORD=An0thrS3crt
ENV MYSQL_USER=mysql_user
ENV MYSQL_DATABASE=mysql_db

# Expose the MySQL port
EXPOSE 3306

# Define a volume for MySQL data
VOLUME ["/var/lib/mysql"]

    