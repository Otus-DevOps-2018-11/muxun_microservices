# muxun_microservices
muxun microservices repository

<details><summary> Домашнее задание №12 docker-1 </summary>\
<p>

* установлен docker из deb пакета
* запущен первый контейнер hello-world
* рассмотрен механизм запуска контейнеров
* рассмотрены команды docker create \ start \ attach \ exec \ commit
* создан образ и лог списка образов добавлен в файл docker-1.log
* изучены выводы команд docker inspect для образа и контейнера
* рассмотрены механизмы остановки контейнров и уничтожения контейнеров и образов


</p>
</details>



<details><summary> Домашнее задание №13 docker-2 </summary>
<p>

* создан новый проект docker
* установлен docker-machine 
* с помощью docker machine создан хост в GCP
* изучен механизм переключения с локального окружения на удаленные в docker-machine
  eval $(docker-machine env dockerhost)
* проверены pid изоляции в контейнере и на хост машине
* созданы необходимые файлы для создания докер образа
* написан dockerfile и собран образ
* добавлено правило файерволла для порта 9292 
* запущен docker контейнер 
 <img src="https://raw.githubusercontent.com/muxun/muxun.github.io/master/docker%20reddit%20machine.png"></img>

* зарегестрировался на docker hub
* запушен образ на docker hub
* проверен локальный запуск docker контейнера из образа с докер-хаба
<img src="https://raw.githubusercontent.com/muxun/muxun.github.io/master/docker%20localhost.png"></img>

* изучены способы остановки\старта\подключения с контейнерами и вывод информации по образам

</p></details>


<details> <summary> Домашнее задание №14 docker-3 </summary>
<p>

* создана файловая структура для микросервисного приложения
* написаны докерфайлы для сервисов 
* собраны образы сервисов
* сборка ui образа начата с шага,отличающегося от сборки образа коммента, так как они имеют одинаковые базовые слои ruby 
* создана сеть приложения
* запущенны контейнеры и проверена работа приложения 
<img src="https://raw.githubusercontent.com/muxun/muxun.github.io/master/docker%20microservices%20app.png"></img>

* произведена попытка улучшения докерфайлов
* создан объект volume для базы данных и пересоздано приложение с этим хранилищем
* созданы записи и комментарии, убиты контейнеры и перезапущенны вновь - информация в бд сохранена

</p>
</details>




