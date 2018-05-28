# Требования к проекту «Telnet-клиент для настройки модемов БТК» #

# Содержание #

1 [Введение](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#1-%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5)

2 [Требования пользователя](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#2-%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)

2.1 [Программные интерфейсы](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#21-%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D1%8B%D0%B5-%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81%D1%8B)

2.2 [Интерфейс пользователя](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#22-%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F)

2.3 [Характеристики пользователей](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#23-%D0%A5%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B8-%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D0%B5%D0%B9)

2.4 [Предположения и зависимости](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#24-%D0%9F%D1%80%D0%B5%D0%B4%D0%BF%D0%BE%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D1%8F-%D0%B8-%D0%B7%D0%B0%D0%B2%D0%B8%D1%81%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8)

3 [Системные требования](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#3-%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)

3.1 [Функциональные требования](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#31-%D0%A4%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)

3.2 [Нефункциональные требования](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Documents/Requirements/Requirements%20Document.md#32-%D0%9D%D0%B5%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)

# 1 Введение #

Проект «Telnet-клиент для настройки модемов БТК» является мобильным приложением для ускорения настройки оборудования у абонентов РУП «Белтелеком». С его помощью можно осуществить базовую настройку модема, а именно сервисы VoIP, ByFly и Wi-Fi. Также доступен ручной режим для других настроек.

# 2 Требования пользователя #

## 2.1 Программные интерфейсы ##

Приложение будет взаимодействовать с сетевым оборудованием через Telnet-протокол.

## 2.2 Интерфейс пользователя ##

Окно выбора адресов по умолчанию или переход в ручной режим.

 ![Рисунок 1](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Images/MainMenu.png)

Окно ввода и отправки базовых настроек

 ![Рисунок 2](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Images/AutoMode.png)

Окно авторизации в ручном режиме
 
 ![Рисунок 3](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Images/ManualModeMenu.png)
 
Окно ввода команд в ручном режиме

 ![Рисунок 4](https://github.com/TischenkoArseny/TRTPO-Project/blob/master/Images/ManualMode.png)
 
## 2.3 Характеристики пользователей ##

Приложение ориентирован в первую очередь на работников РУП «Белтелеком» непосредственно причастных к первичной установке и настройке оборудования у абонентов. Автоматический режим не требует высокого уровня образования и специальных знаний.

## 2.4 Предположения и зависимости ##

Приложение осуществляет обмен с оборудованием по Telnet-протоколу, поэтому в некоторых случаях возможно возникновение трудностей в связи с закрытым доступом в оборудовании.

# 3 Системные требования #

## 3.1	 Функциональные требования ##

3.1.1	Возможность выбор между автоматическим и ручным режимом. Автоматический режим - режим, в котором от пользователя требуется только ввести индивидуальные данные абонента. Ручной режим - режим, в котором пользователь вписывает вручную все запросы.

3.1.2	Возможность ввода индивидуальных данных абонентов: номер и пароль договора ByFly, номер и пароль VoIP, SSID и пароль Wi-Fi.

3.1.3	Возможность настройки Portmapping.

3.1.4	Возможность ввода IP-адреса и логин/пароля в ручном режиме.

3.1.5	Возможность провести тонкую настройку в ручном режиме, под тонкой настройкой подразумеваются такие возможности как отключения режима изоляции между WLAN и LAN, смена приоритета, канала Wi-FI сети.

## 3.2 Нефункциональные требования ##

### 3.2.1 Атрибуты качества ###

3.2.1.1 Требования к удобству пользования

Быстрый доступ к основному функционалу автоматического режима, а именно 2-3 нажатия в зависимости от стартового положения переключателя IP-адреса: 192.168.100.1 или же 192.168.1.1.

3.2.1.2 Ограничения

Приложение устанавливается на смартфоны с ОС Android 5.0+.
