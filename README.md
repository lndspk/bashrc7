# bashrc7
# README.md

by lndspk

aliases some commands to be humorous, not intended for serious use. read the contents of the file for information on what it does.

dependencies:
fortune-mod (or whatever port of openbsd's "fortune" you can use with the same command syntax)

to install:
cd /opt
git clone https://github.com/lndspk/bashrc7
doas chown <user> /opt/bashrc7
doas rm -r ~/.bashrc
doas cp /opt/bashrc7/.bashrc /root/.bashrc
then reload whatever terminal your using
