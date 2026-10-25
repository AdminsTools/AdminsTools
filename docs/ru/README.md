<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/wordmark-dark.png"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/wordmark-light.png" width="420" alt="AdminsTools"></picture></p>

<p align="center"><a href="../../README.md">Türkçe</a> &nbsp;·&nbsp; <a href="../../docs/en/README.md">English</a> &nbsp;·&nbsp; <a href="../../docs/de/README.md">Deutsch</a> &nbsp;·&nbsp; <b>Русский</b> &nbsp;·&nbsp; <a href="../../docs/zh/README.md">中文</a></p>

<p align="center">Набор инструментов сетевого и системного администратора в одном окне: обнаружение, маршрут и скорость, DNS, веб, почта, удалённое управление — без установки, драйверов и учётных записей.</p>

<p align="center"><img src="https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/ping.svg" width="760" alt="Ping-сканирование"></p>

<p align="center">✓ Один файл, без установки &nbsp;·&nbsp; ✓ Не нужны права администратора &nbsp;·&nbsp; ✓ Windows · macOS · Linux &nbsp;·&nbsp; ✓ Данные остаются на компьютере</p>

<p align="center"><a href="http://adminstools.org/downloads/AdminsTools-2.23.0.exe"><b>Windows</b></a> <sub>.exe · ~16 MB</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip"><b>macOS</b></a> <sub>Apple Silicon</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip"><b>macOS</b></a> <sub>Intel</sub> &nbsp;|&nbsp; <a href="http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64"><b>Linux</b></a> <sub>amd64</sub></p>

| **27** | **1** | **256** | **5** | **9** |
|:---:|:---:|:---:|:---:|:---:|
| инструментов в одном окне | файл; без установки | адресов /24 за один проход | языки: TR · EN · DE · RU · 中文 | цветовых тем, включая тёмную |

## Снимки экрана

| Обнаружение | Маршрут и скорость | DNS и адрес | Web | Управление | Расчёт и сведения |
|---|---|---|---|---|---|
| [Ping-сканирование](#t-ping) | [Traceroute / MTR](#t-trace) | [DNS-запрос](#t-dns) | [Сводка HTTP/HTTPS](#t-http) | [Массовая операция](#t-exec) | [Расчёт подсети](#t-subnet) |
| [Сканирование портов](#t-port) | [Тест скорости](#t-speed) | [Whois](#t-whois) | [HTTP-запрос (curl)](#t-curl) | [Mail](#t-mail) | [Этот компьютер](#t-local) |
| [Идентификатор IP](#t-ident) | [Wi-Fi](#t-wifi) | [Мой внешний IP](#t-myip) | [API-клиент](#t-api) | [SNMP](#t-snmp) |  |
| [Производитель по MAC](#t-mac) | [Загрузчик файлов](#t-download) |  | [Сертификат](#t-cert) | [Syslog](#t-syslog) |  |
| [Соседство (LLDP/CDP)](#t-nbr) | [Определение MTU](#t-mtu) |  | [Проверка SSL](#t-ssl) | [Порт: сообщение / прослушивание](#t-send) |  |
|  |  |  |  | [Захват пакетов](#t-capture) |  |
|  |  |  |  | [Wake-on-LAN](#t-wol) |  |

### Обнаружение

<a id="t-ping"></a>

#### Ping-сканирование

/24 за один проход: задержка, ARP, потери, имя и производитель по MAC; 5 пингов или непрерывно на один адрес.

![Ping-сканирование](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/ping.svg)

<a id="t-port"></a>

#### Сканирование портов

Готовые профили, баннеры служб, UDP-зонды; опасные порты отмечены.

![Сканирование портов](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/port.svg)

<a id="t-ident"></a>

#### Идентификатор IP

«Что это за IP?» Ping, порты, SNMP, веб и MAC сводятся в обоснованную оценку с баллами.

![Идентификатор IP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/ident.svg)

<a id="t-mac"></a>

#### Производитель по MAC

MAC → производитель в любом формате; по IP находится MAC. Виртуальные и локально администрируемые адреса отмечены.

![Производитель по MAC](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/mac.svg)

<a id="t-nbr"></a>

#### Соседство (LLDP/CDP)

Обнаружение от коммутатора к коммутатору; имена портов, LAG, семь раскладок, SVG / PNG / PDF.

![Соседство (LLDP/CDP)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/nbr.svg)

### Маршрут и скорость

<a id="t-trace"></a>

#### Traceroute / MTR

Сетевые полосы, потери и задержка на каждом узле, карта мира.

![Traceroute / MTR](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/trace.svg)

<a id="t-speed"></a>

#### Тест скорости

Измерение скорости загрузки и отдачи до интернета или своего сервера.

![Тест скорости](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/speed.svg)

<a id="t-wifi"></a>

#### Wi-Fi

Измеритель сигнала, обзор каналов и карта покрытия.

![Wi-Fi](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/wifi.svg)

<a id="t-download"></a>

#### Загрузчик файлов

Быстрая загрузка в несколько потоков прямо в папку «Загрузки»; проверка SHA-256.

![Загрузчик файлов](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/download.svg)

<a id="t-mtu"></a>

#### Определение MTU

Наибольший пакет, проходящий без фрагментации; обнаружение «чёрных дыр».

![Определение MTU](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/mtu.svg)

### DNS и адрес

<a id="t-dns"></a>

#### DNS-запрос

Типы записей, сравнение нескольких серверов рядом, DNSSEC, AXFR.

![DNS-запрос](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/dns.svg)

<a id="t-whois"></a>

#### Whois

RDAP и классический whois: регистратор, контакты, AS, местоположение, исходная запись.

![Whois](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/whois.svg)

<a id="t-myip"></a>

#### Мой внешний IP

Определение внешнего адреса, провайдера и перенаправления DNS.

![Мой внешний IP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/myip.svg)

### Web

<a id="t-http"></a>

#### Сводка HTTP/HTTPS

Код состояния, перенаправления, заголовки безопасности и определение продукта.

![Сводка HTTP/HTTPS](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/http.svg)

<a id="t-curl"></a>

#### HTTP-запрос (curl)

DNS, TCP, TLS и первый байт по отдельности; в том числе страницы на JavaScript.

![HTTP-запрос (curl)](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/curl.svg)

<a id="t-api"></a>

#### API-клиент

Как Postman, только проще: коллекции, переменные, учётные данные.

![API-клиент](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/api.svg)

<a id="t-cert"></a>

#### Сертификат

Цепочка, срок действия, доверие и версии TLS.

![Сертификат](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/cert.svg)

<a id="t-ssl"></a>

#### Проверка SSL

Оценка A+ … F, близкая к критериям SSL Labs, с причинами.

![Проверка SSL](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/ssl.svg)

### Управление

<a id="t-exec"></a>

#### Массовая операция

Команды на сотнях машин через SSH / WinRM; шаблоны, несколько учётных записей.

![Массовая операция](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/exec.svg)

<a id="t-mail"></a>

#### Mail

SMTP, MX + SPF / DMARC, IMAP / POP3, тестовое письмо и проверка relay.

![Mail](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/mail.svg)

<a id="t-snmp"></a>

#### SNMP

Walk / get, v1–v3; в режиме трансляции компьютер отвечает как SNMP-устройство.

![SNMP](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/snmp.svg)

<a id="t-syslog"></a>

#### Syslog

Отправка сообщения или работа сервером с приёмом входящих.

![Syslog](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/syslog.svg)

<a id="t-send"></a>

#### Порт: сообщение / прослушивание

Отправка сообщения на порт TCP / UDP и просмотр ответа или входящих данных.

![Порт: сообщение / прослушивание](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/send.svg)

<a id="t-capture"></a>

#### Захват пакетов

Лёгкий захват без Npcap, сводка по протоколам и запись в pcap.

![Захват пакетов](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/capture.svg)

<a id="t-wol"></a>

#### Wake-on-LAN

Пробуждение магическим пакетом, и отслеживание включения по ping.

![Wake-on-LAN](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/wol.svg)

### Расчёт и сведения

<a id="t-subnet"></a>

#### Расчёт подсети

Сеть, широковещательный, диапазон адресов, маска и разбиение.

![Расчёт подсети](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/subnet.svg)

<a id="t-local"></a>

#### Этот компьютер

Интерфейсы, adresler, шлюз, DNS и VPN.

![Этот компьютер](https://cdn.jsdelivr.net/gh/AdminsTools/AdminsTools@85c0621f66a0/assets/screens/ru/local.svg)

## Neden AdminsTools

- **Быстрый, но не тормозит компьютер** — Пинги идут равномерным потоком: коммутаторы не перегружаются, ответы не теряются. Программа работает с низким приоритетом на нескольких ядрах.
- **Мощный фильтр** — Готовые кнопки, списки значений со счётчиками, диапазоны и короткий язык запросов: `vendor:hp rtt>20 -down`. Строки не прыгают.
- **История результатов и экспорт** — Каждый запуск сохраняется под своим именем. Excel, CSV, pcap, SVG / PNG / PDF; файлы сразу в папку «Загрузки».
- **Хранилище паролей** — Пароли SSH, WinRM, SNMP v3 и почты хранятся в хранилище, зашифрованном Argon2id + AES-GCM; в файлы настроек и результатов не пишутся.
- **Данные остаются на вашем компьютере** — Без учётных записей, облака и телеметрии. Интерфейс открывается только на 127.0.0.1 и по ключу сеанса.
- **5 языков, 9 тем** — Турецкий, английский, немецкий, русский, китайский. Светлые и тёмные темы; ширина столбцов и виды запоминаются.

## Скачать

Версия 2.23.0 · Один файл: скачайте и запустите. Настройки хранятся в одном файле; положите `PowerAdminTool.json` рядом с exe, и программа будет работать с USB-накопителя.

**Windows** — `AdminsTools-2.23.0.exe · ~16 MB`

- Windows 10 / 11, 64 bit
- Не требует установки и прав администратора
- Ping и traceroute без драйверов

[⤓ Скачать для Windows](http://adminstools.org/downloads/AdminsTools-2.23.0.exe)

**macOS** — `AdminsTools-2.23.0-macos-arm64.zip · -macos-amd64.zip`

- Apple Silicon (M1 и новее) или Intel
- Без подписи: при первом запуске правый щелчок › Открыть
- Захват пакетов в macOS недоступен

[⤓ Apple Silicon](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-arm64.zip) &nbsp;·&nbsp; [⤓ Intel](http://adminstools.org/downloads/AdminsTools-2.23.0-macos-amd64.zip)

**Linux** — `adminstools-2.23.0-linux-amd64 · ~15 MB`

- x86-64, один исполняемый файл
- `-listen 0.0.0.0:8090` — доступ из браузера на jump-сервере
- Для ping: `ping_group_range` или `cap_net_raw`

[⤓ Скачать для Linux](http://adminstools.org/downloads/adminstools-2.23.0-linux-amd64)

---

© 2026 Mehmet Göğebakan
