# Инструкцыя команд в GIT

* 1 Элемент

##  Инструкция по GITHUB

* git clone (ссылка)  клонирование внешнего репозитория на локальный пк
* cd .(путь к папке)  fatal: not a git repository

* <i>git status -  получить информацию от git о его текущем состоянии</i>
* <<code>git add '.\Markdown instruction.md'  добавить файл или файлы к следующему коммиту</code>
* git commit -m "C лекции 1. семинару 1."  Создание коммита
* git log  - вывод на экраны истории всех коммитов с их хеш-кодами
* git diff- увидеть разницу между текущим файлом и закоммиченным файлом
* git checkout - переход от одного коммита к другому
* git checkout master – вернуться к актуальному состоянию и продолжить работу

### Инструкция создания веток

* git branch <название ветки> создать новую ветку
* git checkout (название ветки) – перейти на другую ветку
* что-то изменили
* ctrl + s
* git add  .(путь к файлу)  добавить файл или файлы к следующему коммиту
* git commit -m "название"  Создание коммита
* git checkout master – вернуться к актуальному состоянию и продолжить работу
* изменить в мастере в тех-же строках
* сохранить а потом
* git merge (название ветки) – команда слить ветку
* git branch -d  (название ветки) удалить веку

#### Обшая инструкция

* git init- инициализация локального репозитория
* git status -  получить информацию от git о его текущем состоянии
* git log  - вывод на экраны истории всех коммитов с их хеш-кодами
* git checkout - переход от одного коммита к другому
* git diff- увидеть разницу между текущим файлом и закоммиченным файлом
* clear  - очистить терминал
* git branch  - вывести список всех имеющихся веток
* git branch master  - тоже создать ветку новую открыть главную ветку
* git merge lists – в текущую ветку добавит информацию из ветки  lists
* git log --graph  увидеть лог коммитов с визуализацией между ними
* git pull  - загрузить из хаба
* git push – загрузить в хаб
* git clone (ссылка)  клонирование внешнего репозитория на локальный пк
* git checkout images
* git checkout lists
* git push origin develop  
* git push origin main
* git push –help
* git push -u origin main
* git branch -M main  
* git remote add origin (ссылка)

