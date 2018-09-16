FROM wilkesystems/steamcmd

MAINTAINER su <enmoton@qq.com>

EXPOSE 10999 10888

VOLUME ["/save"]

ADD entrypoint /

RUN steamcmd +login anonymous +force_install_dir /dst +app_update 343050 validate +quit

CMD ["entrypoint"]
