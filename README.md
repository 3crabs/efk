# efk


### Поднять логирование? Легко!
```
echo ELK_VERSION=7.9.2 > .env
sudo docker-compose up
```

Kibana - http://localhost:5601

Login - elastic

Password - changeme

### Создать индекс
logstash-*

### Запускать любые docker контейнеры
```
docker run --log-driver=fluentd tag="docker.{CHANGE_NAME}" ...
```

### Успехов!
