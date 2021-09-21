FROM alpine:3.12
#RUN sudo apt-get update && sudo apt-get upgrade -y
#RUN sudo apt-get install mosquitto-clients -y
ADD subscriber.sh .
ENTRYPOINT subscriber.sh
