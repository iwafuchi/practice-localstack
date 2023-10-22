FROM localstack/localstack
COPY --chown=localstack ../../scripts/init.sh /etc/localstack/init/ready.d/init.sh
RUN chmod 777 /etc/localstack/init/ready.d/init.sh