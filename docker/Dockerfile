FROM  apache/nifi
LABEL maintainer="Milco Numan <milco.numan@syntouch.nl>"
LABEL site="https://www.syntouch.nl/"
# Install some additional stuff 
USER root
RUN   apt-get install -y python3 vim less
# Expose additional port (for receiving requests for Hello World tutorial)
EXPOSE 8090