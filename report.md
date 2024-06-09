
## Contents


1. [Part1. Ready-made docker](#part1-ready-made-docker)  
2. [Part2. Operations with container](#part2-operations-with-container) 
3. [Part3. Mini web server](#part3-mini-web-server) 
4. [Part4. Your own docker](#part4-your-own-docker) 
5. [Part5. Dockle](#part5-dockle) 
6. [Part6. Basic Docker Compose](#part6-basic-docker-compose)


## Part1. Ready-made docker 


![](images/part1/1docker_pull.png)

Скачал с Dockerhub готовый образ

![](images/part1//2docker_images.png)

Проверил в images

![](images/part1/3docker_run.png)

Запустил контейнер с этим образом

![](images/part1/4docker_ps.png)

Посмотрел запущенные контейнеры

![](images/part1/5docker_inspect.png)

Посмотрел информацию о контейнере

![](images/part1/6nginx_ports.png)

Посмотрел на каких портах запущен контейнер

![](images/part1/7inspect_size.png.png)

Проверил что nginx работает

![](images/part1/8docker_stop.png)

Остановил контейнер

![](images/part1/9nginx_ports_and_restart.png)

Запустил контейнер с мостом для сетей через порты

## Part2. Operations with container

![](images/part2/1nginx_it_and_conf.png)

Использование оболочки bash в контейнере и cat 

![](images/part2/2cat_confScreenshot%20from%202024-06-08%2002-18-04.png)

Копирование конфига на "локально" 

![](images/part2/4default_conf.png)

Добавление ручки state

![](images/part2/5cp_and_reload.png)

Копирование конфига и перегрузка ngingx

![](images/part2/6status.png)

Проверка ручки

![](images/part2/7rmi.png)

Удаление image

![](images/part2/8rm_container_and_stop.png)

Остановка и удаление контейнера

![](images/part2/9import_image.png)

Import image

![](images/part2/10run_imported_image.png)

Запуск импортированного имеджа

![](images/part2/11cheching_site.png)

Провкра

## Part3. Mini web server

![](images/part3/1install_nessesary_lib.png)

Установка необходимых библеотек

![](images/part3/2port81.png)

Запуск на 81 порту

## Part4. Your own docker

![](images/part4/1.built_my_image.png)

Билд своего image

![](images/part4/2.маппинг_папки_и_порта.png)

Мапинг папки и портов

![](images/part4/3.check_service.png) 

Проверка сервиса

## Part5. Dockle

![](images/part5/1dockle.png)

Проверка dockle

## Part6. Basic Docker Compose

