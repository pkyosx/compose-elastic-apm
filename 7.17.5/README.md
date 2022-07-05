# Prerequisite

`Install docker and docker-compose beforehand`

# Start service

`docker-compose up -d`

# Visit kibana server URL on host machine

`http://localhost:5601/`

# Install metrics agent (ex. Django)
https://www.elastic.co/guide/en/apm/agent/python/current/django-support.html

# Config APM server URL on host machine
`http://localhost:8200`

# Test sending metrics (ex. Django)
`python manager.py elasticapm test`

# Re-create everything
```
docker-compose down
rm -rf .data
docker-compose up -d
```