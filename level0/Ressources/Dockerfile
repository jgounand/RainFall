FROM debian
RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y binutils
RUN apt install -y gdb
RUN apt install -y git
RUN apt install -y python
RUN apt install -y vim
RUN git clone https://github.com/longld/peda.git ~/peda
RUN echo "source ~/peda/peda.py" >> ~/.gdbinit
