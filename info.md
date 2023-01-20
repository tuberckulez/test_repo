# Инструкци по командам GIT

## Начало работы

Инциализация в git происходит 1 раз, после установки git, с помощью команд:
* git config --global user.name "user-name"
* git config --global user.email email@example.com

## Основные команды

Все команды работают после сохранения файла

+ **git config** - показывает все комманды
+ **git init** - инициализация папки 
+ **git status** - отображение статуса фалов в репозитории
+ **git add name_file** - добавляет name_file в отслеживаемое 
+ **git commit -m "Comment"** - добавляет commit с сообщением Comment. -m - message
+ **git log** - отображает список commit'ов
+ **git checkout 4cb4** - переход к commit'у по адресу 4cb4
+ **git checkout master** - переход к ветке master. Вместо master можно использовать название других веток
+ **git diff** - показывает текущие изменения в сравнении с предыдущим commit'ом


## Команды для ветвей

Ветви нужны для внесения изменений вне главновго ветки

+ **git branch** - просмотр списка ветвей
+ **git branch name_branch** - создание ветви name_branch
+ **git checkout name_branch** - переход к ветви name_branch
+ **git merge name_branch** - слияние текущей ветви с ветвью name_branch
+ **git branch -d name_branch** - удаление ветви name_branch. -d - модификатор удаления

## Команды для работы с удаленным репозиторием

+ **Команда для инициализации локального репозитория в облаке и загрузки кода в гитхаб. (Проводится один раз)** 

    git remote add origin https://github.com/Nflesh/Faso-Geekbrains-Git_instruct.git
        
    git branch -M master
    
    git push -u origin master
    
+ **Отправка кода из инициализированного репозитория**
    
    git push

+ **Загрузка кода из облака в локальный репозиторий**

    git pull

    P.s. При скачивании кода он производит его слияние(merge)

+ **Для отправки отдельной ветвки**

    git push --set-upstream origin name_branch



# Добавление комманд из интернета

## Сайт по изучению Git'а

[Learning Git](https://learngitbranching.js.org/?locale=ru_RU) 
