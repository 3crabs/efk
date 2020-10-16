# efk


### Поднять логирование одной командой
Создать .env
```
ELK_VERSION=7.9.2
```

```
sudo docker-compose up
```

Kibana - http://localhost:5601


### Запускать любые docker контейнеры

```
docker run --log-driver=fluentd ...
```

### Успехов!
