# Что и зачем ?
<li>Этот репозиторий содержит инструкцию по установке и настройке гибкого и стандартного VPN подключения на разных устройствах и операционных систем.</li><br>
<li>- Гибкий VPN - это точный маршрут, куда будет происходить подключение, например только на YouTube, Discord и т.п.(зависит от вас).</li>
<li>- Стандартный VPN - это общий маршрут, действует на сайтов/сервисов(не для игр).</li>

# Как настроить программу, подключиться ? (Windows, для других операционных систем аналогично).

1. Программа с общим VPN доступом(нет гибкой настройки) - скачиваем по ссылке: <link>https://github.com/hiddify/hiddify-app/releases</link>, рекомендую стабильную версию, v2.0.5

<img width="912" height="676" alt="image" src="https://github.com/user-attachments/assets/8f7ed72a-5d89-4534-a3f4-413e79eb38f6" /></br>


2. Для гибкой настройки VPN трафика - Скачиваем программу NekoRay с <link>https://github.com/MatsuriDayo/nekoray/releases</link>, сейчас актуальная версия(не бета) 4.0.1 и распаковываем в удобную папку. <img width="899" height="266" alt="image" src="https://github.com/user-attachments/assets/0b5bf9d5-4cde-4e38-b588-779f5c261162" /><br>

2.1. Для WINDOWS(для других аналогично) - запускаем файл "NekoBox" от имени администратора.<br>

<img width="753" height="728" alt="image" src="https://github.com/user-attachments/assets/a6c55a2b-9534-4e3f-9c96-7f6d6d605bd0" /><br>

В появившимся окне нажимаем на "Программа", после выбираем пункт "Добавить профиль из буфера обмена" (ЗАРАНЕЕ СКОПИРУЙТЕ ЛИЧНЫЙ КЛЮЧ), у нас появляется подключение.<br>

<img width="799" height="628" alt="image" src="https://github.com/user-attachments/assets/f95d0039-326b-4752-a513-00849b4f73fa" /><br>

После требуется установить "режим TUN".<br>

<img width="793" height="622" alt="image" src="https://github.com/user-attachments/assets/cfc8ade7-0496-43b3-bea0-5a31800d9003" /><br>

Теперь можем подключаться: нажав ПКМ(правой кнопкой мыши) по добавленному подключению и выбрав пункт "Запустить" происходит подключение к VPN.

<li>P.s. Если вам требуется маршрутизовать подключение для определенных сайтов, нам нужно проделать несколько этапов настрйоки</li>:
1. Нажать на кнопку "Настройки" -> "Настройка маршрутов".
2. Базовые маршруты.
3. OutBound по умолчанию выбрать "byPass".
4. Указать список доменов(сначала пишем "domain: и после двоеточий пишем домен сайта).
5. Сохраняем настройку(жмем ОК).<br>

<img width="801" height="757" alt="image" src="https://github.com/user-attachments/assets/8f9fa87b-1397-4394-8043-02641e5fdb21" /><br>

# Список доменов есть в файлах:
<li><code>all_Domain`s_list.txt</code> - список запрещенных сайтов.</li>
<li><code>Domain`s_list.txt</code> - сайты: Youtube, ChatGPT, Discord, Instagram, Facebook, Meta, Spotify.</li>

# Для мобильных устройствойств, планшетов(операционная система IOS/Andoid):
1. IOS - переходим в AppStore и скачиввем приложение "Streisand", после копируем приватный ключ и добавляем подключение, перейдя в приложение и жмем на " + ", в правом верхнем углу и выбираемм "Добавить из буфера".<br>

<img width="591" height="1280" alt="image" src="https://github.com/user-attachments/assets/ed1529db-bef0-445c-a506-c2a9ba3a1bcd" /><br>

2. Android - переходим в Google Play / Play Market или альтернативу и скачиваем приложение "v2RayTun", после копируем приватный ключ и добавляем подключение, перейдя в приложение и жмем на " + ", в правом верхнем углу и выбираем "Импорт из буфера обмена".<br>

<img width="1280" height="836" alt="image" src="https://github.com/user-attachments/assets/7003415f-2f93-46e9-ba44-4e4093e09cab" /><br>

