# Use Alpine as the base image
FROM alpine:latest

# Create a script that displays a message and then sleeps
RUN printf '#!/bin/sh\n\
echo "Hello world from Alpine!"\n\
sleep 3600\n' > /hello-world.sh

# Make the script executable
RUN chmod +x /hello-world.sh

# Run the script when the container starts
CMD ["/hello-world.sh"]

