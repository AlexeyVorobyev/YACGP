# Инфраструктурный репозиторий проекта YACGP

## Предполагаемая архитектура
![image](https://github.com/AlexeyVorobyev/YACGP-DevOps/assets/42997441/e9ef5786-9c45-4a21-91d7-efad0894e5ac)

## Команды для работы с GIT

```shell
# git submodules clone
git submodule update --init --recursive
```

```shell
# git submodules update
git submodule update --recursive --remote
```
## Команды для запуска Docker Compose

```shell
# custom network creation
# you should write subnet for your custom network
docker network create --subnet=10.20.0.0/16 yacpg-dev-network
```
