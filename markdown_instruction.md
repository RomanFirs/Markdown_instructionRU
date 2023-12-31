# Инструкция для работы с Git и удалёнными репозиториями

<img src ="https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2014/05/WhatIsMarkdown_Lead_Image.jpg" width="150px">

## Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

Для создание репозитория необходимо выполнить команду *git init* в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add* <имя файла>

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть **ДОБАВЛЕНЫ** и сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.

## Перемещение между сохранениями

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge*

## Удаление веток

Для удаления ветки ввести команду "git branch -d 'name branch'"
# Что такое Markdown

Markdown — это облегченный язык разметки с синтаксисом форматирования обычного текста. Документация поддерживает разметку Markdown в соответствии с CommonMark и ее синтаксический анализ через подсистему Markdig. Документация также поддерживает пользовательские расширения Markdown, которые предоставляют более обширный контент на сайте документации.

# Шпаргалка по синтаксису разметки Markdown

## Создание заголовков

* \# Заголовок 1

* \## Заголовок 2

* \### Заголовок 3

* \#### Заголовок 4

* \##### Заголовок 5

* \###### Заголовок 6

## Ссылки

* Это \[Rambler](https://www.rambler.ru/ "Рамблер") - с тайтлом.

* \[Example](https://example.net) - без заголовка.

* Это \[ссылка]("Агентство TexTerra") - с тайтлом.

* \[Эта ссылка](http://example.net/) - без заголовка.

* \<https://texterra.ru/&gt; – безанкорная ссылка.

## Цитаты

* \> Все, что делаешь, надо делать хорошо, даже если совершаешь безумство.
<br>
Оноре де Бальзак ©

* \> Не пробуй - делай.<br>
Магистр Йода ©

* \> Ты недооцениваешь мою мощь. 
<br>
Энакин Скайуокер ©

## Выделения текста
Форматирование курсивом и жирным точно есть во всех инструментах, где другие функции Markdown могут быть ограничены. Синтаксис выделения текста и расставления акцентов:

* \__Жирный__

* \**Тоже жирный**

* \*Курсив*

* \_Тоже курсив_

* \~~Зачеркнутый~~

Можно легко комбинировать эти способы выделения.

## Списки и отступы
Чтобы оформить строку в элемент маркированного списка, в начале нужно поставить плюс, минус или звездочку. Звездочка не приведет к курсивному выделению, потому что отделяется от слова пробелом.

- Пункт 1

- Пункт 2

- Пункт 3

или

+ Пункт 1

+ Пункт 2

+ Пункт 3

или

* Пункт 1

* Пункт 2

* Пункт 3

<img src = "https://texterra.ru/upload/medialibrary/b36/81xs1gyyrpuyu7gmuwfztwnwc147ceni/4.webp">
<br>
Если необходимо создать нумерованный список, используйте в начале строки цифру с точкой. Удобно, что нумерация автоматическая: можно вставить любые цифры, и ошибки не будет.

1. Пункт 1

2. Пункт 2

3. Пункт 3

или

1. Пункт 1

1. Пункт 2

1. Пункт 3

или даже

9. Пункт 1

5. Пункт 2

1. Пункт 3

<img src = "https://texterra.ru/upload/medialibrary/b68/05ova58bqtt5ks3zelhytsztvnm6a21j/5.webp">
<br>
Маркдаун-разметка также позволяет оформлять многоуровневые списки. Уровень обозначается не количеством спецсимволов, как в случае с заголовками, а за счет отступов. Проще не считать пробелы, а каждый новый подпункт выделять табуляцией.

- Пункт 1

        - Подпункт A

                - Подподпункт a

- Пункт 2

        + Подпункт A

                * Подподпункт a

---

1. Пункт 1

        + Подпункт A

                - Подподпункт a

2. Пункт 2

        1. Подпункт 2.1.

                1. Подподпункт 2.1.1

3. Пункт 3

<img src = "https://texterra.ru/upload/medialibrary/bac/uqpuavasiihcam3i8apvbgcrhzsaj0r7/6.webp">
<br>
Если пункт списка включает несколько строк или абзацев, нужно соблюдать всё те же отступы, чтобы было красиво оформлено. Ключевые мысли в списках также можно выделять другой разметкой, например, жирным. Примеры:

* __Тезис №1__

    Раскрываем тезис.

* __Тезис №2__

    Раскрываем тезис.

---

* __Тезис №1__ Раскрываем тезис.

* __Тезис №2__ Раскрываем тезис.

<img src = "https://texterra.ru/upload/medialibrary/c7e/a2zqcschn5k7pt51huuc13t4hybjcn1e/7.webp">

## Изображения

Для того, чтобы вставить изображение не обязательно перемещать в репозиторий файл этого изображения, можно ссылаться на файл из инетрнета через ссылку: 

* [текст](url изображания) - в этом случае вы будете видеть кликабельную строку с названием __"текст"__

* \![картинка](url изображения) - при добавлении **"!"** вы будете видеть визуализацию изображения

Пример: 

* [текст](https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp)
<br>
* ![картинка](https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp)

Размер изображений можно изменять, для этого нужно использовать следующую команду: 

* \<img src = "url изображения" width = "15px"> , где "px" изменяемая величина, влияющая на размер изображения.

Пример:

* <img src = "https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp" width = "15px">

* <img src = "https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp" width = "30px">

* <img src = "https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp" width = "40px">

* <img src = "https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp" width = "55px">

* <img src = "https://texterra.ru/upload/medialibrary/312/bd0mepuypjdjyr9eytlavyklc0bku0eg/10.webp" width = "90px">

## Экранирование

Мы разобрали с десяток различных символов, которые используются в разметке Markdown. Но что если эти символы нужны нам в самом тексте? Чтобы спецсимволы не исчезали и не влияли на оформление, нужно использовать экранирование. Как и во многих других языках программирования, этим целям служит обратная косая черта (бэкслеш).

<img src = "https://texterra.ru/upload/medialibrary/3d4/b7h4iy3m8mzc7b5ipg7vbyy7eliu9ave/15.webp">
<br>
Исключение – когда надо вставить внутри кода грависы (обратные тики). Интерпретатор не посчитает их за обозначение инлайн-кода, если только весь участок кода заключен с двух сторон в двойные грависы. Ничего не понятно? На примере все наглядно:
<br>
<img src = "https://texterra.ru/upload/medialibrary/886/fps1tlq1beyvj79br0uuvdrgi7npjras/16.webp">
<br>
В отличие от HTML, в Markdown не нужно специально экранировать амперсанд (&) или угловую скобку (<).

## Инструменты для работы с маркдаун-разметкой

1. [Markdown Here](https://markdown-here.com/livedemo.html/ "Press") – простейший сервис для проверки разметки и практики работы с языком.

3. [Markdown Editor](https://jbt.github.io/markdown-editor/ "Press") – тоже довольно простой редактор, но с возможностью открывать и сохранять в MD/HTML, есть ночной режим.

8. [Dillinger](https://dillinger.io/ "Press") – более функциональный, но тоже бесплатный онлайн-инструмент. Есть автосохранение, подсчет слов и символов. Работает импорт и сохранение в Medium, GitHub, Dropbox, Google Drive. Экспортирует не только в HTML и MD, но и в PDF.

2. [Writebox](https://write-box.appspot.com/ "Press") – веб-редактор для любителей минимализма. Есть синхронизация с Dropbox и Google Drive, настройка горячих клавиш, скачивание документов в текстовом и HTML-формате.

7. [Codepen](https://codepen.io/ "Press") – платформа для фронтенд-разработки, тоже хорошо подойдет для работы с Markdown, HTML и другими языками.

10. [Typora](https://www.typora.io/ "Press") – бесплатный, простой и мощный редактор Markdown для Windows, MacOS (beta-версия) и Linux. Ориентирован на создателей текстового контента. Имеет не отвлекающий режим, который позволяет лучше сосредоточится на творческой работе.

11. [Atom](https://github.blog/2022-06-08-sunsetting-atom/ "Press") – бесплатный редактор исходного кода для Windows, Linux, MacOS. Распознает множество языков программирования, в том числе маркдаун-разметку.

12. [Jekyll](https://jekyllrb.com/ "Press") – генератор статичных сайтов, работает в том числе с MD-файлами.

13. [Hexo](https://hexo.io/ru/ "Press") – тоже генератор, но ориентированный на создание блогов. Поддерживает расширенный синтаксис Markdown.
 
## Всё про слияние

Ветка master
Мастер - это основная ветка проекта, в которую заливается только рабочий проверенный код. Новый функционал в конце концов оказывается в мастере.

В различных компаниях и командах могут быть приняты другие соглашения насчет веток. Например, что весь функционал сначала сливается в промежуточную ветку. 

 ## Что такое мердж или слияние веток
Это перенос кода из одной ветки в другую. Например, когда мы заканчиваем работу над веткой, например, сделали новый функционал или поправили багу, мы сливаем ее в мастер. В мастере код проверяется еще раз и выкладывается на боевой сервер.

Сливать друг в друга можно любые ветки. Технически, с точки зрения git нет никакой разницы, сливается ветка с новым функционалом в мастер или наоборот. Для нас мастер - это основная ветка разработки, а для git это просто ветка.

Разница логическая

Мы будем говорить, что новая ветка сливается в мастер, когда мы закончили работать над функционалом и хотим выложить его на боевой сайт. Тогда мы сливаем ветку в мастер и выкладываем мастер в продакшен.

Мастер сливается в ветку или мастер подтягивается в ветку, когда мы продолжаем работать над веткой, но хотим периодически подтягивать новые коммиты с сервера - новый код, который написали наши коллеги. Если работа над веткой идет довольно долго, есть смысл подтягивать изменения из мастера хоть каждый день.

Следует четко различать мердж своей ветки в мастер и мердж мастера в свою ветку.

Мердж ветки в мастер
Выполняется после завершения работы над своей веткой при помощи команды git merge. Чтобы вмерджить ветку в мастер, нужно сначала перейти в мастер, а затем выполнить git merge branch_name.

    git checkout master
    git merge news

Пока мы работали над веткой, в мастере не появилось новых коммитов, Git понимает, что это новый код, который можно просто положить поверх старого. Это простая ситуация и git не задает никаких вопросов.

Теперь другая ситуация.

Что если сначала не подтягивать мастер, а смерджить свою ветку
Принципиально ничего не изменится, но лучше сначала сделать актуальной ветку мастер, а уже потом заливать свои изменения. А еще лучше держать актуальной свою ветку относительно мастера. Это значит, что стоит почаще подтягивать мастер в свою ветку. Таким образом мы в своей ветке будем работать с актуальным кодом и у нас меньше риска что-нибудь поломать. А если поломаем, то лучше чинить это в своей ветке, а не в мастере.

Чем чаще мерджить между собой ветки, тем больше появляется так называемых мердж-коммитов. Такой коммит появляется каждый раз, когда мы подтягиваем мастер в свою ветку или сливаем свою ветку в мастер. Эти коммиты не хранят изменений, они хранят только факт мерджа одной ветки в другую.

## Полезное 

![картинка](https://s2.studylib.es/store/data/008825178_1-f39e56009941736933e722fe371a5cd3.png)
<br>
![картинка](https://res.cloudinary.com/practicaldev/image/fetch/s--2PiSwXn3--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://pbs.twimg.com/media/EezubrwUYAAo8UP.png)


## Заметка для себя: данная иструкция не является исчерпывающей и может быть дополнена.

<img src ="https://res.cloudinary.com/practicaldev/image/fetch/s--tl1bwCNQ--/c_imagga_scale,f_auto,fl_progressive,h_1080,q_auto,w_1080/https://dev-to-uploads.s3.amazonaws.com/i/kc1str971ujjedi3h32i.png" width="200px">