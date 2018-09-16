FROM wilkesystems/steamcmd

MAINTAINER su <enmoton@qq.com>

EXPOSE 10999 10888

VOLUME ["/save"]

RUN steamcmd +login anonymous +force_install_dir /dst +app_update 343050 validate +quit

ADD entrypoint /
RUN chmod +x entrypoint

CMD ["/entrypoint"]
