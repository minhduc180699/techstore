FROM elasticsearch:7.12.1

RUN apt-get update && apt-get install -y \
    apt-get install openjdk-8-jdk \
    && rm -r /var/lib/apt/lists/*
# Create user
RUN useradd -m -s /bin/bash minhduc \
    && usermod -a -G www-data minhduc
