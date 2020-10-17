FROM ubuntu:xenial

RUN apt-get update \
  && apt-get dist-upgrade -qy \
  && apt-get install -qy \
  bind9-host \
  curl \
  dnsutils \
  fping \
  iproute2 \
  iputils-ping \
  jq \
  openssh-client \
  tcpdump \
  traceroute \
  tshark \
  vim \
  && apt-get -qy autoremove \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/* /root/.cache
