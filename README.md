Alpine docker image for [Celery
Flower](https://flower.readthedocs.org/en/latest/).

Usage:

```bash
docker run -p 5555:5555 -v /etc/localtime:/etc/localtime:ro \
    robbieclarken/flower --broker=amqp://$RABBIT_HOST:5672// [FLOWER-OPTIONS]
```
