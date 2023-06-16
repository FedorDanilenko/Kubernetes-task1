## Разветка приложения в Kubernetes

Задание: написать приложение на Python, упаковать это приложение в Docker, Написать helm-чарт для развертывания этого приложения в Kubernetes.

Образ докера загружен на docker-hub: johnmorg/kuber
## Запуск

1. Скопировать данный репозиторий с GitHub напрямую с сайта или используя команду:
```shell
git clone https://github.com/FedorDanilenko/Kubernetes-task1.git
```
2. Выполнить следующие команды в скачанном каталоге:
```shell
helm package .
helm install myapp app-0.1.0.tgz
```

