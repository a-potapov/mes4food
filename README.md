﻿<!-- В таких стрелочках указывается комментарий. Он не будет виден на странице, только в исходниках. -->
<!-- Поля к заполнению указаны в <треугольных скобках>, комментарий под ними - описание этого поля. -->
<!-- Если какой-то пункт не применим к проекту - удалите его. -->

# mes4food. Справка
<!-- Уникальное имя проекта для использования в других сервисах как ключ. Обычно совпадает с именем клиента для однокомандной разработки или ИмяКлиента_ИмяКоманды для мультикомандной. -->

<details><summary>Оглавление</summary>

[[_TOC_]]

</details>

## Основное

[Чек-лист по разворачиванию проекта](https://konstanta.gitlab.io/wiki/plan/New/New_project/)

- **<abbr title="Регламентация, тестовый запуск, запущено, сопровождение. Может быть указано несколько статусов, если по разным подсистемам он разный.">Статус проекта:</abbr>** <Статус проекта>
- **<abbr title="Клиент и ссылка на него в рабочей базе.">Клиент:</abbr>** <Клиент> <Навигационная ссылка на РБ>
- **<abbr title="Ссылка на битрикс на команды, участвующие в этом проекте.">Команды:</abbr>** <Команды>

### Подсистемы

<details><summary>Описание подсистем</summary>

<!-- Какие подсистемы/блоки учета реализованы или в процессе реализации. Кто принимал участие в разработке, какой тег в обсуждениях-->

#### <Имя подсистемы>

- **Методолог:** <Методолог> (<Предыдущие методологи, если есть>)
- **Архитектор:** <Архитектор> (<Предыдущие архитекторы, если есть>)
- **Принимали участие:** <Список людей через запятую>
- **Тег в обсуждениях:** <Имя тега>

#### <Имя подсистемы2>

- **Методолог:** <Методолог> (<Предыдущие методологи, если есть>)
- **Архитектор:** <Архитектор> (<Предыдущие архитекторы, если есть>)
- **Принимали участие:** <Список людей через запятую>
- **Тег в обсуждениях:** <Имя тега>

</details>

### Параметры подключения

<details><summary>Инструкции по подключению</summary>

<!-- VPN, RDP, ссылка на инструкции по подключению-->

**<abbr title="Кто поможет с подключением">Ответственный:</abbr>** <Ответственный>

</details>

## Ответственные

- **Руководитель проекта:** <Руководитель проекта> <!-- Сохранять историю-->
- **Аккаунтер:** <Аккаунтер> <!-- Сохранять историю-->
- **Методолог:** <Методолог> <!-- Сохранять историю-->
- **Архитектор:** <Архитектор> <!-- Сохранять историю-->
- **Релиз-инженер:** <Релиз-инженер> <!-- Сохранять историю-->
- **Кто пишет сценарии:** <Кто пишет сценарии> <!-- Сохранять историю-->
- **Кто пишет тест-кейсы:** <Кто пишет тест-кейсы> <!-- Сохранять историю-->
- **Кто пишет тесты:** <Кто пишет тесты> <!-- Сохранять историю-->
- **Кто пишет документацию:** <Кто пишет документацию> <!-- Сохранять историю-->
- **<Роль>:** <Исполнитель> <!-- Сохранять историю-->

## Коммуникации

<details><summary>Описание коммуникаций</summary>

### Связь с клиентом

<!-- Контактное лицо, телефон, почта, скайп, должность, по каким вопросам обращаться или ссылка на элемент РБ, где указаны контакты-->

**<abbr title="Кто поможет с коммуникациями">Ответственный:</abbr>** <Ответственный>

### Чаты

<!-- Список чатов для обсуждения проекта. Внутренние на команду и общие с клиентом.-->

- **[<Имя чата>](<Ссылка на чат>)** - <Описание чата>
- **[<Имя чата>](<Ссылка на чат>)** - <Описание чата>

#### Служебные чаты

<!-- Чаты, в которые выводится различная нотификация - от гитлаба, от дженкинса и аналоги-->

- **[<Имя чата>](<Ссылка на чат>)** - <Описание чата>
- **[<Имя чата>](<Ссылка на чат>)** - <Описание чата>

**<abbr title="Кто поможет с чатами">Ответственный:</abbr>** <Ответственный>

### Взаимодействие с пользователями

<!-- Процедура взаимодействия. Есть ли тех. поддержка, как пользователи обращаются в тех.поддержку, как тех.поддержк обращается к команде, сколько уровней тех.поддержки -->
<!-- TODO: Добавить ссылку на статью из вики -->

**<abbr title="Кто поможет с взаимодействием">Ответственный:</abbr>** <Ответственный>

</details>

## Рабочая база

- **<abbr title="Версия платформы, на которой работает рабочая база. Может не совпадать с целевой версией разработки">Версия платформы:</abbr>** <Версия платформы> <!-- TODO: Извлечь из мониторинга -->
- **Используемая БД:** MS SQL 2019 | MS SQL 2017 | MS SQL 2016 | MS SQL 2014 | PostgreSQL | Файловая
- **Размер БД:** <Размер БД> <!-- TODO: Добавить ссылку на статью из вики -->
- **Количество пользователей:** <Количество пользователей в базе> <!-- TODO: Извлечь из мониторинга -->

<details><summary>Как получить бекап/базу для расследования или разработки</summary>

<!-- Процедура получения бекапа для расследования. База еще маленькая и можно выгрузить дт, или можно подключится к клиенту и на его сервере развернуть копию, или можно перебросить скульный бекап в сеть Константы и развернуть базу. -->
<!-- TODO: Добавить ссылку на статью из вики -->

**<abbr title="Кто поможет с получением бекапа">Ответственный:</abbr>** <Ответственный>

</details>

<details><summary>Технологические окна</summary>

<!-- Время, когда допустимо обновлять рабочую базу. Подробнее ниже в разделе Деплой -->

**<abbr title="Кто поможет с окнами">Ответственный:</abbr>** <Ответственный>

</details>

<details><summary>Оборудование</summary>

<!-- Какое оборудование используется и как его отлаживать -->
<!-- TODO: Добавить ссылку на статью из вики -->

**<abbr title="Кто поможет с оборудованием">Ответственный:</abbr>** <Ответственный>

</details>

<details><summary>Интеграции</summary>

<!-- Какие с проектом есть интеграционные швы, ссылки на описания и пояснения -->
<!-- TODO: Добавить ссылку на статью из вики -->

**<abbr title="Кто поможет с интеграциями">Ответственный:</abbr>** <Ответственный>

</details>

# Расположения

| Имя | Ссылка | **<abbr title="Кто поможет с доступом">Ответственный</abbr>** |
| ------ | ------ |------ |
| **<abbr title="Каталог на NAS или в другом общедоступном месте, где хранится информация по проекту.">Общий каталог</abbr>** | <Общий каталог> | <Ответственный> |
| **<abbr title="Ссылка на Регламенты, концепции">Предпроектные документы</abbr>** | <Ссылка на предпроектные документы> | <Ответственный> |
| **<abbr title="Ссылки на Устав проекта, модель">Проектные документы</abbr>** | <Ссылка на проектные документы> | <Ответственный> |
| **<abbr title="Инструкции, справка, документация">Пользовательская документация</abbr>** | <Ссылка на пользовательскую документацию> | <Ответственный> |
| **<abbr title="Ссылка на список инцидентов и процедуры по работе с ними">Инциденты</abbr>** | <Ссылка на список инцидентов> | <Ответственный> |
| **<abbr title="Ссылка на тесты и процедуры по работе с ними">Тесты</abbr>** | <Ссылка на тесты> | <Ответственный> |

## Иерархия проектов

- **<abbr title="При мультикомандной разработке гитлаб-проектов может быть несколько, на каждую команду. Но должен быть основной, в которой выгружается код, уходящий в прод. Тут указывается этот самый основной, если он есть.">Родительский проект:</abbr>** <Родительский проект> 

<details><summary>Дочерние проекты</summary>

<!-- Если этот проект является родительским, то тут нужно указать ссылки на проекты, которые являются ответвлением от текущего и его выполняют другие команды -->

- **[<Имя проекта>](<Ссылка на проект>)** - <Описание проекта>
- **[<Имя проекта>](<Ссылка на проект>)** - <Описание проекта>

</details>

## Базы

<!-- Указываются базы: -->
<!-- Адрес рабочей базы: Параметры подключения к рабочей базе клиента. Если проект уже запущен, то лучше скрыть эту информацию во избежания случайного захода -->
<!-- Базы в сети клиента: Все базы, которые используются на стороне клиента. Препрод, база тестирования, база для расследования со свежим бекапом, базы разработки итп -->
<!-- Базы в нашей сети: Клиент-серверные базы используемые под проект. Перечисляются как общие базы, так и личные базы разработки. Если есть файловые базы, общие для всей команды, то их тоже стоит перечислить. -->

| Имя базы | **<abbr title="Рабочая, препрод, тестирование, разработка, демо">Назначение</abbr>** | Строка подключения | **<abbr title="Кто поможет с доступом и кто может сказать, используется база или нет">Ответственный</abbr>** | Комментарий |
| ------ | ------ | ------ | ------ | ------ |
| **<Имя базы>** | <Тип базы> | <Строка подключения> | <Ответственный> | <Комментарий> |
| **<Имя базы>** | <Тип базы> | <Строка подключения> | <Ответственный> | <Комментарий> |
| **<Имя базы>** | <Тип базы> | <Строка подключения> | <Ответственный> | <Комментарий> |
| **<Имя базы>** | <Тип базы> | <Строка подключения> | <Ответственный> | <Комментарий> |

# Разработка

<details><summary>Параметры и процедуры разработки</summary>

## Как начать разработку

<!-- Как и где получить дт или базу в которой можно начать вести разработку, что нужно прочитать, где нужно отметится (например в этом файле) -->

- **<abbr title="Версия платформы, на которой ведется разработка. Должна совпадать с версией рабочей базы или должна быть описана причина расхождения">Целевая версия платформы:</abbr>** <Целевая версия платформы>
- **Используемый префикс:** `к2|кс|кс_|_`
- **<abbr title="Особенности в разработке, есть ли отличия от стандатов 1С и соглашений .">Соглашения по разработке:</abbr>** https://konstanta.gitlab.io/wiki/create/Conventional/Dev/ , https://its.1c.ru/db/v8std
- **Схема разработки:** `Хранилище|ЕДТ|Гибридная (хранилище и ЕДТ)|Конфигуратор + Гит`
- **Используемые линтеры:** <Список линтеров>  <Используемые профили и настройки>  <!-- TODO: Добавить ссылку на статью из вики -->
- **Использование прекоммита:** <Да/Нет>  <Ссылка на настройки> <!-- TODO: Добавить ссылку на статью из вики -->
- **Использование форматтера:** <Да/Нет>  <Ссылка на настройки> <!-- TODO: Добавить ссылку на статью из вики -->
- **<abbr title="Кто может помочь с началом разработки">Ответственный:</abbr>** <Ответственный>

- **Проект в гит-конверторе:** <Ссылка на проект>
- **<abbr title="Кто может помочь со сломавшимся конвертором или сказать, актуальный проект или нет">Ответственный за гит-конвертор:</abbr>** <Ответственный>

## Хранилища

### Процедура работы с хранилищами

<!-- Используется разветвленная разработка на хранилищах, одно хранилище на команду или не используется в принципе -->
<!-- TODO: Добавить ссылку на статью из вики -->

### <abbr title="Хранилище, где программисты программируют. Она же dev-ветка">Основное хранилище разработки</abbr>

- **<abbr title="Какие доработки и кому допустимо делать в этом хранилище">Назначение:</abbr>** <Назначение хранилища>
- **<abbr title="Не рекомендуется использовать">Файловый путь:</abbr>** `\\srv-dev\Repository\<Имя проекта>`
- **Серверный путь:** `tcp://178.249.64.178:1542/<Имя проекта>` `8.3.18.1661` 
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **<abbr title="Кто может помочь с доступом к основному хранилищу">Ответственный:</abbr>** <Ответственный>

<details><summary>Служебные пользователи</summary>

<!-- В список пользователей нужно добавлять только служебных: для работы скриптов, инструментов и отчетов. Конкретных пользователей для разработки и тестирования указывать не стоит. -->

| Служебный пользователь | Пароль | Назначение |
| ------ | ------ |------ |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |

</details>

### <abbr title="Хранилище, в котором стоит поддержка от типовой, библиотек или ERP4FOOD. Может совпадать с хранилищем разработки. Обычно master-ветка. А поддержка хранится в upstream-ветка">Хранилище обновления поддержкой</abbr>

- **<abbr title="Какие доработки и кому допустимо делать в этом хранилище">Назначение:</abbr>** <Назначение хранилища>
- **<abbr title="Не рекомендуется использовать">Файловый путь:</abbr>** `\\srv-dev\Repository\<Имя проекта>`
- **Серверный путь:** `tcp://178.249.64.178:1542/<Имя проекта>` `8.3.18.1661` 
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **<abbr title="Кто может помочь с доступом к основному хранилищу">Ответственный:</abbr>** <Ответственный>

<details><summary>Служебные пользователи</summary>

<!-- В список пользователей нужно добавлять только служебных: для работы скриптов, инструментов и отчетов. Конкретных пользователей для разработки и тестирования указывать не стоит. -->

| Служебный пользователь | Пароль | Назначение |
| ------ | ------ |------ |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |

</details>

### <abbr title="Хранилище, из которого собирается релиз. Обычно совпадает с хранилищем разработки. В нем должны лежать только проверенные доработки.">Релизное хранилище</abbr>

- **<abbr title="Какие доработки и кому допустимо делать в этом хранилище">Назначение:</abbr>** <Назначение хранилища>
- **<abbr title="Не рекомендуется использовать">Файловый путь:</abbr>** `\\srv-dev\Repository\<Имя проекта>`
- **Серверный путь:** `tcp://178.249.64.178:1542/<Имя проекта>` `8.3.18.1661` 
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **<abbr title="Кто может помочь с доступом к основному хранилищу">Ответственный:</abbr>** <Ответственный>

<details><summary>Служебные пользователи</summary>

<!-- В список пользователей нужно добавлять только служебных: для работы скриптов, инструментов и отчетов. Конкретных пользователей для разработки и тестирования указывать не стоит. -->

| Служебный пользователь | Пароль | Назначение |
| ------ | ------ |------ |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |

</details>

### <abbr title="Если используется разветвленная разработка, то от какого хранилища было ответвленно">Вышестоящее хранилище</abbr>

- **<abbr title="Какие доработки и кому допустимо делать в этом хранилище">Назначение:</abbr>** <Назначение хранилища>
- **<abbr title="Не рекомендуется использовать">Файловый путь:</abbr>** `\\srv-dev\Repository\<Имя проекта>`
- **Серверный путь:** `tcp://178.249.64.178:1542/<Имя проекта>` `8.3.18.1661` 
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **<abbr title="Кто может помочь с доступом к основному хранилищу">Ответственный:</abbr>** <Ответственный>

<details><summary>Служебные пользователи</summary>

<!-- В список пользователей нужно добавлять только служебных: для работы скриптов, инструментов и отчетов. Конкретных пользователей для разработки и тестирования указывать не стоит. -->

| Служебный пользователь | Пароль | Назначение |
| ------ | ------ |------ |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |

</details>

<!-- Если существуют еще хранилища, то нужно скопировать блок про хранилище и заполнить его. -->

## Расширения

<!-- TODO: Добавить ссылку на статью из вики -->

- **Использование расширений:** <Не используются/Формат использования(только патчи, демо-функционала, весь функционал разрабатывается только в расширениях)>
- **<abbr title="Где и как хранится информация об используемых расширениях">Учет расширений:</abbr>** <Процедура учета расширений или ссылка на нее>
- **<abbr title="Процедура разработки и деплоя расширений">Разработка расширений:</abbr>** <Процедура или ссылка на нее>
- **<abbr title="Кто может помочь с расширениями на проекте">Ответственный:</abbr>** <Ответственный>

## ЕДТ

<!-- TODO: Добавить ссылку на статью из вики -->

- **Использование ЕДТ:** <Не используются/Процедура использования> <!-- В каких ветках разрабатывать, как сливать изменения, используется ли строгая типизация, используемый профиль в проверках -->
- **Версия ЕДТ:** <Версия ЕДТ>
- **Плагины:** <Ссылки на плагины>
- **Параметры:** `<Рекомендуемые параметры>` <!-- Например, `-Xmx12g` -->
- **<abbr title="Кто может помочь с ЕДТ на проекте">Ответственный:</abbr>** <Ответственный>

</details>

# Тестирование

<details><summary>Процедуры тестирования и параметры</summary>

<!-- TODO: Добавить ссылку на статью из вики -->

- **<abbr title="Где расположены тесты">Расположение:</abbr>** <Ссылка на гитлаб-проект или на каталог> <!-- Дублирует информацию из общих расположений -->
- **<abbr title="Кто может помочь с тестами на проекте">Ответственный:</abbr>** <Ответственный> <!-- Дублирует информацию из раздела с ответственными -->

## Процедура тестирования

<!-- Кто и когда пишет тест-кейсы, кто и когда проверяет по ним. Используются ли автоматические тесты. -->

## Как запустить тесты локально

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Как программисту или аналитику запустить тесты. -->

## Дымовые тесты

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Используются ли дымовые тесты и где они расположены. Как их актуализировать. Как их запустить -->

## Используемые дт

<!-- Где расположены дт и для каких тестов их стоит использовать -->

</details>

# Поддержка

<details><summary>Информация о поставках, на поддержке от которых стоит конфигурация</summary>

- **Поддержка конфигурации**
    - **<abbr title="Имя конфигураций от которых стоит поддержка. Для проектов на коробке это ERP4FOOD, для проектов на типовых - имя типовой ERP, УТ, КА итп. Для конфигураций, разрабатываемых с нуля - библиотеки БСП, БПО итп.">Поддержка:</abbr>** <Поддержка> <!-- TODO: Автоматизировать заполнение -->
    - **Версия поддержки:** <Версия поддержки>  <!-- TODO: Автоматизировать заполнение -->
    - **<abbr title="Кто, как и когда обновляет поддержку. На что нужно обратить внимание при обновлении, как проверить, что все хорошо.">Процедура обновления поддержки:</abbr>** <Ссылка на процедуру обновления>
    - **<abbr title="Кто обновляет поддержку">Ответственный:</abbr>** <Ответственный>
- **Тесты**
    - **<abbr title="Кто, как и когда обновляет тесты. На что нужно обратить внимание при обновлении, как проверить, что все хорошо.">Процедура обновления тестов:</abbr>** <Ссылка на процедуру обновления>
    - **<abbr title="Кто обновляет тесты">Ответственный:</abbr>** <Ответственный>
- **Обновляемость**
    - **Ссылка на проект обновляемости:** <Ссылка>
    - **Баллов обновляемости:** <Баллов обновляемости> <!-- TODO: Автоматизировать заполнение -->
    - **<abbr title="Кто контролирует проект обновляемости">Ответственный:</abbr>** <Ответственный>

## Лицензирование

<!-- TODO: Добавить ссылку на статью из вики -->

- **Отгруженная лицензия:** <Ссылка>  <!-- Ссылка на документ "Отгруженная лицензия" в базе Мониторинга -->
- **Регистрация лицензии:** <Ссылка>  <!-- Ссылка на документ "Регистрация лицензия" в базе Мониторинга, по которой создана лицензия -->
- **<abbr title="К кому обратится для получения лицензии в базу разработки">Кто выдает лицензии:</abbr>** <Ответственный>

<!-- Описание лицензирования, если используются и другие продукты с лицензиями -->

</details>

# Подготовка релиза

<details><summary>Что нужно сделать, чтобы выпустить релиз</summary>

<!-- TODO: Добавить ссылку на статью из вики -->

- **<abbr title="Ответственный за подготовку релиза">Релиз-инженер:</abbr>** <Релиз-инженер>
- **Подготовка конфигурации**
    - **<abbr title="Ответственный за подготовку конфигурации">Ответственный:</abbr>** <Ответственный>
    - **Процедура подготовки к релизу**: <Ссылка на процедуру>
    - **Запуск сонара**: <Ссылка на пайплайн, который запускает сонар>
    - **Сонар**: <Ссылка на проект в сонаре>
    - **Запуск тестов**: <Ссылка на пайплайн, который запускает тесты>
    - **Запуск тестов**: <Ссылка на пайплайн, который запускает тесты> <!-- Если пайплайнов несколько -->
    - **Запуск тестов**: <Ссылка на пайплайн, который запускает тесты> <!-- Если пайплайнов несколько -->
- **Подготовка документации**
    - **<abbr title="Ответственный за подготовку документации по релизу">Ответственный:</abbr>** <Ответственный>
    - **Процедура обновления документации**: <Ссылка на процедуру>
- **Подготовка описания релиза**
    - **<abbr title="Ответственный за подготовку описания релиза">Ответственный:</abbr>** <Ответственный>
    - **Процедура подготовки описания релиза**: <Ссылка на процедуру>

</details>

# Обновление РБ (Деплой)

<details><summary>Как обновлять РБ</summary>

<!-- TODO: Добавить ссылку на статью из вики -->

## Согласование обновления РБ

**<abbr title="Ответственный за согласование обновления">Ответственный:</abbr>** <Ответственный>

<!-- Кого и когда нужно уведомить со стороны клиента об обновлении. Кого и когда нужно уведомить со стороны команды. Кто должен дать разрешения, без которых обновления не запускаются. -->

## Обновление РБ

**<abbr title="Ответственный за обновление">Ответственный:</abbr>** <Ответственный>

<!-- Процедура обновления, чек-лист, инструкция или ссылки на них. -->

<!-- Если обновление РБ происходит без релизного хранилища, то удалить блок про хранилище -->

### <abbr title="Хранилище, через которое в рабочую базу клиента доставляются обновления. К этому хранилищу должны быть подключены только рабочая база, база обновления и базы тестирования.">Хранилище, подключенное к РБ</abbr>

- **<abbr title="Какие доработки и кому допустимо делать в этом хранилище">Назначение:</abbr>** <Назначение хранилища>
- **<abbr title="Не рекомендуется использовать">Файловый путь:</abbr>** `\\srv-dev\Repository\<Имя проекта>`
- **Серверный путь:** `tcp://178.249.64.178:1542/<Имя проекта>` `8.3.18.1661` 
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **Серверный путь:** `tcp://178.249.64.178:<Порт>/<Имя проекта>` `<Версия платформы>` <!-- Если доступно несколько серверов -->
- **<abbr title="Кто может помочь с доступом к основному хранилищу">Ответственный:</abbr>** <Ответственный>

<details><summary>Служебные пользователи</summary>

<!-- В список пользователей нужно добавлять только служебных: для работы скриптов, инструментов и отчетов. Конкретных пользователей для разработки и тестирования указывать не стоит. -->

| Служебный пользователь | Пароль | Назначение |
| ------ | ------ |------ |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |
| `<Пользователь хранилища>` | `<Пароль>` |`<Назнчачение>` |

</details>

</details>

# Операции на РБ (OPS)

<details><summary>Поддержка, мониторинг, аллертинг и инциденты</summary>

## Первая линия тех. поддержки

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Кто оказывает консультацию пользователей -->

## Мониторинг

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Какая информация автоматически собирается в рабочей базе - ошибки в журнале регистрации, замеры производительности, работа оборудования итп -->

## Аллертинг

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- На какие события настроена рассылка оповещений -->

## Инциденты

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Процедура работы с инцидентами -->

</details>

# Мероприятия и ритуалы

<details><summary>Описание периодических мероприятий и ритуалов на проекте</summary>

## Постановочные совещания

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Еженедельники

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Ежедневники

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Ретроспективы

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Внутренние демо

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Демо клиенту

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

## Аудиты

<!-- TODO: Добавить ссылку на статью из вики -->
<!-- Описание мероприятия, его расписание, состав людей -->

</details>

