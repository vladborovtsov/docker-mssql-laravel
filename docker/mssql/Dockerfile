FROM microsoft/mssql-server-linux:latest

RUN \
apt-get update && \
apt-get install -y python sudo

ENV SA_PASSWORD=Password1234
ENV ACCEPT_EULA=Y


# set locale
RUN locale-gen en_US.UTF-8 && update-locale
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8



EXPOSE 1433

