#Starts from ubuntu:22.04
FROM ubuntu:22.04

# Install curl
RUN apt-get update && apt-get install -y curl

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Copy script.sh to /usr/src/app
Copy script.sh .

# Alternatively, if we skipped chmod earlier, we can add execution permissions during the build.
RUN chmod +x script.sh

EXPOSE 8080

# Run the script.sh script
CMD ./script.sh

