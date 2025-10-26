FROM debian:latest
RUN apt-get update && apt-get install -y --no-install-recommends \
    postgresql-client \
    iputils-ping \
    ca-certificates \
    curl \
    less \
    nano \
 && rm -rf /var/lib/apt/lists/*
CMD ["/bin/bash"]