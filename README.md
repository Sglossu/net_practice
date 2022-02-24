# NetPractice

### Учимся настраивать небольшие сети, основываясь на работе TCP/IP

Если вы не знаете что такое IP-адрес, маска подсети или как работает
маршрутизация, почитать подробнее можно
[здесь](https://github.com/evgenkarlson/ALL_SCHOOL_42/blob/master/00_Projects__(Основное_Обучение)/00_Global_(begin_cadet)/02____netwhat/answers_to_netwhat.md)
а также посмотреть [здесь](https://www.youtube.com/watch?v=rLUzYeLdM0k).

> __Таблица маршрутизации__ - электронная база данных в маршрутизаторе, 
> которая представляет из себя некий набор правил.
> В ней содержится информация о сетевых маршрутах по которым определяется наилучший путь
> для передачи пакета данных. Она содержит в себе адрес и маску сети
> подключения, адрес шлюза (т. е. маршрутизатора сети, на который отправляются данные),
> метрику (расстояние) и интерфейс (имя и индентификатор устройства).

> __Коммутатор (switch)__ - устройство для соединения нескольких устройств
> в _одной сети_. У всех устройств одинаковая маска.

> __Роутер (маршрутизатор)__ - сетевой компьютер, который обрабатывает
> полученные данные по заданным правилам администратора
> и опираясь на таблицу маршрутизации определяет
> путь для пересылки данных.

Перед выполнением заданий не забываем главного:
+ Последний IP-адрес подсети - _широковещательный_
+ Первый IP-адрес подсети - _адрес сети_
+ IP-адреса соседних сетей не должны перекрываться
+ IP-адреса `10.0.0.0-10.255.255.255`, 
`172.16.0.0-172.31.255.255` и от `192.168.0.0` до `192.168.255.255` 
зарезервированы для частных адресов, диапазон `127.0.0.1-127.255.255.254`
зарезервирован
для коммуникации с самим собой, остальные-для публичных IP-адресов
+ В таблице маршрутизации `default` или `0.0.0.0/0` соответствуют всему
+ У роутера для каждой подсети своя маска

p.s.: нумерация пунктов для заполнения в каждом задании не просто так придумана :)
___



<details>
  <summary>Level 1</summary>
  <img src="https://github.com/Sglossu/NetPractice/blob/main/img/1.png?raw=true" alt="level1"></img>
</details>

<details>
  <summary>Level 2</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/2.png" alt="level2"></img>
</details>

<details>
  <summary>Level 3</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/3.png" alt="level3"></img>
</details>

<details>
  <summary>Level 4</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/4.png" alt="level4"></img>
</details>

<details>
  <summary>Level 5</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/5.png" alt="level5"></img>
</details>

<details>
  <summary>Level 6</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/6.png" alt="level6"></img>
</details>

<details>
  <summary>Level 7</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/7.png" alt="level7"></img>
</details>

<details>
  <summary>Level 8</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/8.png" alt="level8"></img>
</details>

<details>
  <summary>Level 9</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/9.png" alt="level9"></img>
</details>

<details>
  <summary>Level 10</summary>
  <img src="https://raw.githubusercontent.com/Sglossu/NetPractice/img/10.png"></img>
</details>
