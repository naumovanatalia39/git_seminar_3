# **Основные команды GIT**

>* **git init** - инициализация локального репозитория;

>* **git status** - получить информацию от GIT о его текущем состоянии;


>* **git add** - добавить файл в отслеживание *(к следующему коммиту)*;

>* **git commit** -m "message" - создание коммита;

***Важно писать понятные коммиты***

>* **git log** - вывод на экран истории всех коммитов с их хеш кодами;

>* **git checkout** - переход от одного коммита к другому;

*После этой команды нужно добавить 4 первые цифры хеш кода*

>* **git checkout master** - вернуться к актуальному состоянию и продолжить работу;


>* **git diff** - увидеть разницу между текущим файлом  закоммиченным файлом;

## **Справочные материалы по Markdown**

![https://learn.microsoft.com/ru-ru/contribute/markdown-reference]()

![](https://img.freepik.com/premium-vector/the-end-hand-written-lettering-on-black_116399-28.jpg?w=740)

# Основные команды веток GIT

> * **git branch** - посмотреть список веток в репозитории;

> * **git commit -am"message"** - добавление файлов в отслеживание и создание коммита;

*это 2 команды "git add .> + <git commit -m"message"> в одной. Важно, работает только после применения хотя бы одного раза "git add ."*;

> * **git branch <branch_name>** - создание ветки с названием branch_name;

> * **git checkout -b <branch_name>** - создание ветки и переход к ней;

> * **git branch -d <branch_name>** - удалить ветку с именем branch_name;

> * **clear** - очистка текста в терминале (для удобства);

>* **git log --graph** - вывод на экран истории всех коммитов со всех веток с их хеш-кодами в древовидной форме;

>* **git merge --abort** - отменить слияние, произошедшее с конфликтом;

>* **git merge <branch_name>** - слияние веток, добавляем в ветку, в которой находимся ветку branch_name;

# Основные команды 3 семинара по удалённому репозиторию

>* **git clone <url>** - клонирование внешнего (удаленного) репозитория на локальный ПК;

>* **git pull** - получение изменений и слияние с локальной версией;