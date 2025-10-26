FROM archlinux:latest
RUN pacman -Sy
RUN pacman -S gcc --noconfirm
WORKDIR /app
ADD main.c main.c
RUN gcc main.c -o /app/hello
ENTRYPOINT ["/app/hello"]