workerbeat: sh -c 'cd sites && exec ../env/bin/python -m frappe.celery_app beat -s scheduler.schedule'
web: bench serve
worker: sh -c 'cd sites && exec ../env/bin/python -m frappe.celery_app worker'
redis_cache: redis-server config/redis.conf