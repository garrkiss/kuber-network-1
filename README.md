# Домашнее задание к занятию "`Сетевое взаимодействие в K8S. Часть 1`" - `Бакулев Евгений`

## Задание 1. Создать Deployment и обеспечить доступ к контейнерам приложения по разным портам из другого Pod внутри кластера


- [Манифест Deployment](https://github.com/garrkiss/kuber-app/blob/main/manifest/nginx-multitool-deployment.yaml)
- [Манифест Service](https://github.com/garrkiss/kuber-app/blob/main/manifest/pod-multitool.yaml)
- [Манифест Pod](https://github.com/garrkiss/kuber-app/blob/main/manifest/svc-nginx-multitool.yaml)

![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/1.png)

### Проверка доступности из отдельного пода multitool
![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/2.png)

## Задание 2. Создать Service и обеспечить доступ к приложениям снаружи кластера

- [Манифест Deployment](https://github.com/garrkiss/kuber-app/blob/main/manifest/nginx-deployment.yaml)
- [Манифест Service](https://github.com/garrkiss/kuber-app/blob/main/manifest/svc-nginx.yaml)

![Ссылка](https://github.com/garrkiss/kuber-app/blob/main/img/3.png)