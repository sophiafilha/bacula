FROM sophiafilha/bacula-base:9.6.5

MAINTAINER connectnowconsultoria@gmail.com

VOLUME ["/opt/bacula/etc"]

EXPOSE 9101/tcp

ENTRYPOINT ["bacula-dir"]

CMD ["-f", "-c", "/opt/bacula/etc/bacula-dir.conf"]
