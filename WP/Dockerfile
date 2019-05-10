FROM wordpress:latest
LABEL version="AC_WP_v2"
WORKDIR /home/anna/ProjetDocker/WPMY_app/WP
RUN apt-get update && apt-get install -y iputils-ping
RUN echo "FIN Installation Paquets WP V2" > /home/anna/ProjetDocker/WPMY_app/WP/Status_Paquets_WP.txt
VOLUME /data/vol_WPMY_WP
ENV my_hostname TICTOC
CMD ["/bin/bash", "-c", "while true; do echo WELCOME on A.C. WP Server from $my_hostname and $HOSTNAME V2; sleep 10; done"]
