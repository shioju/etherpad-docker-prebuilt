FROM shioju/mysql:latest

RUN chmod 770 -R /var/lib/mysql /var/log/mysql

ENTRYPOINT ["tail"]
CMD ["-f", "/dev/null"]
