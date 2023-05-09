# estudo_celery

#para rodar o flower
celery flower -A tasks

#para rodar o celery
celery -A tasks worker --loglevel=INFO