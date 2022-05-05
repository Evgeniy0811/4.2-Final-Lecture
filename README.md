Тема: «4.2. Заключительная лекция»

Перечень автоматизируемых сценариев:

1. На главной страницe сайта Netology.ru, с помощью выпадающего меню "Каталог курсов" -> Программирование -> Тестировщик ПО;
2. На главной странице сайта Netology.ru, с помощью выпадающего меню "Каталог курсов" -> Полный каталог -> фильтр "Программирование" -> Тестировщик ПО;
3. На главной странице сайта Netology.ru, с помощью медиа-контента "НЕО для начинающих" -> фильтр "Программирование" -> Тестировщик ПО;

Тестовые сценарии:

Позитивные:

Авторизоваться на сайте Netology.ru;

1. Открыть форму записи на курс обучения, выбрав один из вариантов поиска формы, Поля "Имя" и "Телефон" заполнены автоматически; Нажать на кнопку "Записаться".

Ожидаемый результат:

Появляется сообщение: "Заявка принята. В ближайшее время с Вами свяжется наш менеджер".


Негативный тест:

Авторизоваться на сайте Netology.ru;

 Открыть форму записи на курс обучения, выбрав один из вариантов поиска формы,В поля "Имя" и "Телефон" ввести невалидные данные,Нажать на кнопку "Записаться"

Ожидаемый результат:

Появляются сообщения об ошибках под полями ввода, запись не осуществляется.


Позитивные:

Авторизоваться на сайте Netology.ru;

Открыть форму записи на курс обучения,Заполнение формы именем на латинице (от 2-х символов), номер телефона валидными данными, нажатие на кнопку Записаться. Успешная отправка формы.


Негативный тест:

Открыть форму записи на курс обучения, выбрав один из вариантов поиска формы;В поле "Имя" ввести невалидные данные,В поле "Телефон" ввести невалидные данные,В поле "Электронная почта" ввести невалидные данные,Нажать на кнопку "Записаться"

Ожидаемый результат:

Появляются сообщения об ошибках под полями ввода, запись не осуществляется.

Перечень используемых инструментов:

IntelliJ IDEA 2021.3.2 - функциональная среда разработки, подходящая для многих языков программирования;
Java 11 - объектно-ориентированный язык программирования, оптимальный для написания понятных и наглядных автотестов;
Gradle - мощная и простая система автоматической сборки проектов;
Selenide - изящный API, простота использования;
JUnit-5 - один из самых популярных фреймфорков для модульного тестирования ПО,
Lombok - позволяет оптимизировать код автотестов, добавляет в Java новые «ключевые слова»,
Git и GitHub - для хранения кода,
Gradle либо Maven — системы автоматической сборки,
Браузеры: Google Chrome, Mozilla Firefox,
DBeaver, для просмотра базы данных; если будет предостален "слепок" SUT, то необходим доступ к удаленному серверу с предустановленными.

Перечень необходимых разрешений/данных/доступов:

Разрешение на проведение автоматизированного тестирования сайта Netology.ru;
Доступ к базе данных сайта Netology.ru;
Доступ к БД для проверки результатов отправки валидных/невалидных тестовых данных через Форму для записи Netology.ru;
Тех. документация, чтобы понимать какие данные будут являться валидными, а какие - нет.
Возможное изменение верстки (поведения) и селекторов страницы.

Перечень и описание возможных рисков при автоматизации:
Возможность удаления обучаемой профессии
Возможность изменения структуры сайта
Авто-тесты не проверяют графическую составляющую, а именно едет ли верстка при тех или иных действиях, комфортна ли выбранная цветовая схема оформления и тд.
Возможность изменения количества обязательных полей ввода данных, как для авторизованных, так и для неавторизованных пользователей сайта.

Перечень необходимых специалистов для автоматизации:
Будет достаточно одного автоматизатора тестирования, который умеет работать с указанными выше инструментами.

Интервальная оценка с учётом рисков (в часах):

Для написания тестов и тестирования, подготовки отчетности необходимо 40 часов рабочего времени.


