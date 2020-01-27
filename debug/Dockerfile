FROM ubuntu

RUN apt-get update && \
    apt-get install -y curl \
        dnsutils \
        iputils-ping \
        iproute2 \
        netcat \
        socat \
        vim \
        wget \
        tzdata \
        iperf3 \
        conntrack \
        net-tools \
        dnsdiag \
        inetutils-traceroute \
        tcptraceroute \
        traceroute \
    && rm -rf /var/lib/apt/lists/* 

