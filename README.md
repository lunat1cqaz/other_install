# Что и зачем ?
<li>Этот репозиторий содержит инструкцию по установке и настройке гибкого и стандартного VPN подключения на разных устройствах и операционных систем.</li><br>
<code>Гибкий VPN - это точный маршрут, куда будет происходить подключение, например только на YouTube, Discord и т.п.(зависит от вас).</code><br>

<code>Стандартный VPN - это общий маршрут, действует на сайтов/сервисов(не для игр).</code>

# Как настроить программу, подключиться ? (Windows, для других операционных систем аналогично).

<li>1. Программа с общим VPN доступом(нет гибкой настройки) - скачиваем по ссылке: <link>https://github.com/hiddify/hiddify-app/releases</link>, рекомендую стабильную версию, v2.0.5</li><br>

<img width="906" height="620" alt="image" src="https://github.com/user-attachments/assets/ff368c8c-c261-434b-b2bf-da8fa2d606eb" /><br>

Далее копируем персональный ключ и добавляем маршрут в программе.<br>

<img width="847" height="656" alt="image" src="https://github.com/user-attachments/assets/a537a5c3-f9cb-4f82-a3b6-caf0780fbea2" />

Запускать и останавливать работу по кнопке<br>

<img width="843" height="652" alt="image" src="https://github.com/user-attachments/assets/18a2c082-b8d6-4d19-97b5-5d8094d860a9" />

<li>2. Для гибкой настройки VPN трафика - Скачиваем программу NekoRay с <link>https://github.com/MatsuriDayo/nekoray/releases</link>, сейчас актуальная версия(не бета) 4.0.1 и распаковываем в удобную папку.</li>
<img width="917" height="314" alt="image" src="https://github.com/user-attachments/assets/4444fff7-50c6-407b-a3df-aa50a1278b25" /><br>

<li>2.1. Для WINDOWS(для других аналогично) - запускаем файл "NekoBox" от имени администратора.</li><br>

<img width="753" height="728" alt="image" src="https://github.com/user-attachments/assets/a6c55a2b-9534-4e3f-9c96-7f6d6d605bd0" /><br>

В появившимся окне нажимаем на "Программа", после выбираем пункт "Добавить профиль из буфера обмена" (ЗАРАНЕЕ СКОПИРУЙТЕ ЛИЧНЫЙ КЛЮЧ), у нас появляется подключение.<br>

<img width="799" height="628" alt="image" src="https://github.com/user-attachments/assets/f95d0039-326b-4752-a513-00849b4f73fa" /><br>

После требуется установить "режим TUN".<br>

<img width="793" height="622" alt="image" src="https://github.com/user-attachments/assets/cfc8ade7-0496-43b3-bea0-5a31800d9003" /><br>

Теперь можем подключаться: нажав ПКМ(правой кнопкой мыши) по добавленному подключению и выбрав пункт "Запустить" происходит подключение к VPN.

<li>P.s. Если вам требуется маршрутизовать подключение для определенных сайтов, нам нужно проделать несколько этапов настрйоки:</li><br>
1. Нажать на кнопку "Настройки" -> "Настройка маршрутов".<br>
2. Базовые маршруты.<br>
3. OutBound по умолчанию выбрать "byPass".<br>
4. Указать список доменов(сначала пишем "domain: и после двоеточий пишем домен сайта).<br>
5. Сохраняем настройку(жмем ОК).<br>

<img width="801" height="757" alt="image" src="https://github.com/user-attachments/assets/8f9fa87b-1397-4394-8043-02641e5fdb21" /><br>

# Где взять адрес домена ?
Можно найти на просторах интернета либо:<br>
<li><a href="https://github.com/lunat1cqaz/other_install/blob/main/All_Domain's_list.txt">All_Domain`s_list.txt</a> - список запрещенных сайтов.</li>
<li><a href="https://github.com/lunat1cqaz/other_install/blob/main/Domain%60s_list.txt"></link">Domain`s_list.txt</a> - домены сайтов(подготовлено для NekoRay(nekobox программы)): Youtube, ChatGPT, Discord, Instagram, Facebook, Meta, Spotify.</li>

# Для мобильных устройствойств, планшетов, телевизоров (операционная система IOS/Andoid):
1. IOS - переходим в AppStore и скачиввем приложение "Streisand", после копируем приватный ключ и добавляем подключение, перейдя в приложение и жмем на " + ", в правом верхнем углу и выбираемм "Добавить из буфера".<br>

<img width="591" height="1280" alt="image" src="https://github.com/user-attachments/assets/ed1529db-bef0-445c-a506-c2a9ba3a1bcd" /><br>

2. Android - переходим в Google Play / Play Market или альтернативу и скачиваем приложение "v2RayTun", после копируем приватный ключ и добавляем подключение, перейдя в приложение жмем на " + ", в правом верхнем углу и выбираем "Импорт из буфера обмена".<br>

<img width="1280" height="836" alt="image" src="https://github.com/user-attachments/assets/7003415f-2f93-46e9-ba44-4e4093e09cab" /><br>

3. Anroid TV/Приставка - устанавливаем приложение " v2RayTun ", перейдя в придожение жмем на " + ", в правом верхнем углу и выбираем "Импорт из файла" и выбираем файл (формат файла ".json").<br>

<li>Открыть файл с расширением ".json" можно с носителя(флешка, жесткий диск и т.п., предварительно его туда скопировав).</li><br>

<li>p.s. Можно скачать приложение с сайта https://v2raytun.ru.uptodown.com/android , он будет с расширением APK, его копируем на сторонний носитель(флешку, переносной жесткий диск и т.п.) и вставляем носитель в устройство(телевизор/приставка), находим файл и открыв его - устанавливаем.</li><br>

<img width="985" height="718" alt="image" src="https://github.com/user-attachments/assets/8ed9eded-4311-4d3e-9489-c46df5c0339e" /><br>


# Исходные ссылки на программы:
1. https://github.com/hiddify/hiddify-app?tab=readme-ov-file
2. https://github.com/MatsuriDayo/nekoray
3. https://github.com/StreisandEffect/streisand
