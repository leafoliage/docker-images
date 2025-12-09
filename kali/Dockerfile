FROM kalilinux/kali-rolling

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        openvpn iputils-ping tmux netcat-openbsd vim openssh-client wordlists iproute2 nfs-common  \
        metasploit-framework && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
