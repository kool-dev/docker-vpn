FROM archlinux:latest

# enable kool CLI to exec commands as super user
RUN useradd -g 0 kool

RUN pacman -Syu --noconfirm
RUN pacman -S --noconfirm openssl ppp openfortivpn openssh
RUN pacman -Scc --noconfirm
VOLUME ["/etc/openfortivpn/"]

ENTRYPOINT ["openfortivpn"]
