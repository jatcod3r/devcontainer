FROM ubuntu

RUN apt-get update
RUN apt-get install vim sudo curl net-tools -y

RUN useradd -m -s /bin/bash -G sudo jupepe

USER jupepe

# Let's add a fancy prompt!
RUN echo "PS1='🐳 \[\033[1;36m\]\h \[\033[1;34m\]\W\[\033[0;35m\] \[\033[1;36m\]# \[\033[0m\]'" > ~/.bashrcd