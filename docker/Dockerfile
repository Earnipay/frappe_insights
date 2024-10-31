# Use frappe/bench as the base image
FROM frappe/bench:latest AS development

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the init.sh script from the current context to the container
COPY init.sh ./init.sh


# Run the init.sh script when the container starts
CMD ["bash", "./init.sh"]