# Задание 1.

---

Изобразить с помощью элементов SVG флаги пяти стран: Россия, Франция, Финляндия, Швейцария, Япония.

Каждый SVG-элемент с флагом должен иметь размер 180 на 120 пикселей.

---

# Задание 2.

---

Сверстайте кнопку, которая будет содержать в себе [icon_01](https://icons.getbootstrap.com/icons/arrow-down-left-circle/) (как в примере в последнем видео). При клике на кнопку иконка должна меняться на [icon_02](https://icons.getbootstrap.com/icons/arrow-down-left-circle-fill/). Повторный клик меняет иконку обратно.

---

# Задание 3.

---

Сверстайте кнопку, клик на которую будет выводить на экран следующие данные:

1. Размеры экрана пользователя (ширина и высота).
2. Координаты местонахождения пользователя. Если пользователь отказался дать доступ к местоположению или данная функция недоступна в бразуере, вывести вместо координат сообщение «Информация о местоположении недоступна».

---

# Задание 4.

---

Сверстайте кнопку, по клику на которую будет отправляться запрос к Timezone API. В запросе нужно отправить координаты местоположения пользователя, полученные с помощью Geolocation API. В ответ на запрос придёт объект, из которого нужно вывести на экран следующую информацию:

* временная зона, в которой находится пользователь: параметр *__timezone__*;
* местные дата и время: параметр *__date_time_txt__*.
Строка запроса к API выглядит следующим образом:

[https://api.ipgeolocation.io/timezone?apiKey=32bcd4a6e4b548968e7afcdb682ac679&lat=latitude&long=longitude].

Вместо *__latitude__* и *__longitude__* нужно подставить широту и долготу.

---

# Задание 5.

---

1. Реализовать чат на основе эхо-сервера wss://echo.websocket.org/
Интерфейс состоит из `input`, куда вводится текст сообщения, и кнопки «Отправить».

При клике на кнопку «Отправить» сообщение должно появляться в окне переписки.

Эхо-сервер будет отвечать вам тем же сообщением, его также необходимо выводить в чат:
![](https://lms.skillfactory.ru/assets/courseware/v1/8f6c994ffb9a1526f2b678588ddc8ae4/asset-v1:SkillFactory+PHPPRO+2022+type@asset+block/m15_practice1.png)

2. Добавить в чат механизм отправки гео-локации:
![](https://lms.skillfactory.ru/assets/courseware/v1/368e7971c720c3eb6441642afe77b9b8/asset-v1:SkillFactory+PHPPRO+2022+type@asset+block/m15_practice2.png)

При клике на кнопку «Гео-локация» необходимо отправить данные серверу и в чат вывести ссылку на [https://www.openstreetmap.org/](https://www.openstreetmap.org/) с вашей гео-локацией. __Сообщение, которое отправит обратно эхо-сервер, не выводить__.

---
