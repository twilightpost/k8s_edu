FROM fedora
MAINTAINER shubhra <shubhrajyoti@hotmail.com>

RUN dnf -y update && dnf install -y procps-ng iproute openssh-server && \
    yum clean all

CMD ["/usr/sbin/sshd"]
    
