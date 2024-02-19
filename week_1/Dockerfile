FROM ubuntu:latest

# Đặt biến môi trường USER
ENV USER=root

# Cập nhật các gói phần mềm và cài đặt lxde, tightvncserver, và nano
RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y xorg lxde-core tightvncserver nano && apt-get clean && rm -rf /var/lib/apt/lists/*

# Tạo file xstartup mới
RUN mkdir ~/.vnc && echo "#!/bin/bash\nxrdb $HOME/.Xresources\nlxsession &" > ~/.vnc/xstartup && chmod +x ~/.vnc/xstartup

# Tạo mật khẩu cho VNC
RUN echo "lenghia1007" | vncpasswd -f > ~/.vnc/passwd && chmod 600 ~/.vnc/passwd

# Expose cổng 5901 để kết nối VNC
EXPOSE 5901

CMD ["/bin/bash"]
