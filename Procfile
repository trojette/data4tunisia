## Uncomment lines given your setup and workflow.

## That first line actually launch the local web server,
## we prefer to do that manually to avoid mixing these
## logs with all other dependencies but YMMV
web: udata serve --host 0.0.0.0

## Launch Celery workers (required)
worker: udata work
beat: udata beat

## Uncomment the following lines only if you are not using Docker.
## You'll probably have to adapt your configuration paths (here for homebrew).
#mongodb: mongod --config /usr/local/etc/mongod.conf
#es: elasticsearch --config=/usr/local/opt/elasticsearch17/config/elasticsearch.yml
#redis: redis-server
