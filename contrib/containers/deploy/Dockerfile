FROM phusion/baseimage:focal-1.0.0
LABEL maintainer="VirsAI Developers <dev@virsai.org>"
LABEL description="Dockerised VirsAI, built from Travis"

ARG USER_ID
ARG GROUP_ID

ENV HOME /home/virsai

# add user with specified (or default) user/group ids
ENV USER_ID ${USER_ID:-1000}
ENV GROUP_ID ${GROUP_ID:-1000}
RUN groupadd -g ${GROUP_ID} virsai && \
    useradd -u ${USER_ID} -g virsai -s /bin/bash -m -d /home/virsai virsai && \
    mkdir /home/virsai/.virsai && \
    chown ${USER_ID}:${GROUP_ID} -R /home/virsai

COPY bin/* /usr/local/bin/

RUN chmod a+x /usr/local/bin/*

USER virsai

VOLUME ["/home/virsai"]

EXPOSE 16541 9999 26541 26542

WORKDIR /home/virsai
