FROM centos

RUN yum install -y mock rpm-build rpmdevtools

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /usr/bin/

RUN chmod +x /usr/bin/wait-for-it.sh

ADD entrypoint.sh /tmp/entrypoint.sh

ENTRYPOINT ["/tmp/entrypoint.sh"]
