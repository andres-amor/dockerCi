FROM arangodb:3.1.22

ENV ARANGO_RANDOM_ROOT_PASSWORD=1
WORKDIR /usr/bin

COPY arangobackup /scripts/
RUN chmod +x /scripts/arangobackup
