# docker build -t meklund/systemf-gh-action:$(date +%Y-%m-%d) .
# docker push meklund/systemf-gh-action
FROM ubuntu
RUN apt-get update
RUN apt-get update
RUN apt-get install -y git build-essential autotools-dev automake libtool bison flex lcov python3 gdbserver
COPY systemf-build systemf-gdbserv systemf-check systemf-release-build systemf-sleep-infinity /usr/bin/
