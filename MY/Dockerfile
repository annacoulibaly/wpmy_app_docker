FROM mysql:5.7
LABEL version="AC_MY_v3"
WORKDIR /home/anna/ProjetDocker/WPMY_app/MY
RUN apt-get update && apt-get install -y iputils-ping
RUN echo "FIN Installation Paquets MY V3" > /home/anna/ProjetDocker/WPMY_app/MY/Status_Paquets_MY.txt
VOLUME /data/vol_WPMY_DB
ENV my_hostname TICTAC
CMD ["/bin/bash", "-c", "while true; do echo WELCOME on A.C. Mysql Server from $my_hostname and $HOSTNAME V3; sleep 10; done"]
