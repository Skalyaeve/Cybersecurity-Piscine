FROM            debian:latest

RUN             apt-get update -y               \
                && apt-get install iproute2 -y  \
                && apt-get install net-tools -y \
                && apt-get install libpcap-dev -y

COPY            Inquisitor /usr/bin/Inquisitor

CMD             ["sleep", "infinity"]