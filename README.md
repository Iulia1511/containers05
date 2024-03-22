# Лабораторная работа №5
## Цель работы
Выполнив данную работу студент сможет управлять взаимодействием нескольких контейнеров.
## Задание
Создать php приложение на базе двух контейнеров: nginx, php-fpm.
### Создайте файл .gitignore в корне проекта и добавьте в него строки:
Ignore files and directories
mounts/site/*
![image](https://github.com/Iulia1511/containers05/assets/159126852/02e211da-dc00-4d2f-a34f-35eba1e5f90a)
### Создайте в директории containers05 файл nginx/default.conf со следующим содержимым:
![image](https://github.com/Iulia1511/containers05/assets/159126852/e25b28c1-73d0-42ee-83d8-b5a9d4eaf7b6)
### Создайте контейнер backend и frontend со следующими свойствами:
![image](https://github.com/Iulia1511/containers05/assets/159126852/5dfce28a-a5cf-4f6c-84d8-4fd425b282b3)
![image](https://github.com/Iulia1511/containers05/assets/159126852/df485db7-f3f5-43e5-92d0-de92ebe0ee25)
### Проверьте работу сайта в браузере, перейдя по адресу http://localhost. Если отображается базовая страница nginx, то перегрузите страницу.
![image](https://github.com/Iulia1511/containers05/assets/159126852/2a012b09-dea2-40d3-8f80-7c7284bd75ce)




