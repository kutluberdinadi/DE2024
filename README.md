# DOCKER
## Установка Docker
# Обновила список пакетов
```
apt-get update
```
# Установила пакет
```
apt-get install docker-engine
```
# Добавила утилиту в автозагрузку
```
systemctl enable --now docker
```
# Установила контейнер hello-world
```
docker run hello-world
```
# Удалила контейнер hello-world
```
docker image rm -f hello-world

