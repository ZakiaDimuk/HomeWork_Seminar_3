# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
*Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.*

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### **Git add**
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### **Создание ветки**

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Работа с картинками
Для добавления картинки необходимо найти картинку в интернете и скопировать URL картинки, а затем написать следующее:
![Картинка c телепузиками](https://upload.wikimedia.org/wikipedia/ru/thumb/c/cc/Teletubbies.jpg/274px-Teletubbies.jpg)

![Картинка с Карлсоном и  малышом](https://upload.wikimedia.org/wikipedia/ru/thumb/8/81/%D0%9C%D0%B0%D0%BB%D1%8B%D1%88_%D0%B8_%D0%9A%D0%B0%D1%80%D0%BB%D1%81%D0%BE%D0%BD.jpg/274px-%D0%9C%D0%B0%D0%BB%D1%8B%D1%88_%D0%B8_%D0%9A%D0%B0%D1%80%D0%BB%D1%81%D0%BE%D0%BD.jpg)

## Добавление ссылок
Для того, чтобы добавить ссылки необходимо скопировать URL-адрес и совершить следующее действие:

[Работа_с_markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)
[Работа_с_markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)

## Работа со списками

Нумерованные списки оформляются следующим образом:
1. Один
2. Два

Ненумерованные списки:

* Один
* Два

Существует такой вариант:

+ Один
+ Два

И еще один пример:

- Один
- Два

Важно знать, что, если использовать разные варианты, то между строчками будет разный интервал:

+
+

-
-
## Работа с цитатами

Для одиночной цитаты используется знак ">"
> Мы получаем от жизни то, во что верим... Верьте в себя, верьте в новый день, верьте только в лучшее

Для добавления цитаты под цитатой или автора цитаты используется знак ">>"
>> LIMERENCE

>Позволь каждой ошибке научить тебя великому уроку: каждый закат - это начало очень-очень яркого и большого рассвета.
>> LIMERENCE
